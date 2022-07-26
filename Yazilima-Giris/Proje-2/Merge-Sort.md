# Merge Sort
https://app.patika.dev/alibaris

# Proje-2

## 1. Soru

 **[16,21,11,8,12,22]**

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Merge Sort yöntemine göre dizi her adımda ikiye bölünerek tek bir eleman kalana kadar bölme işlemine devam edilir. Daha sonra birleştirme işlemi yapılır. Sıralama işlemi elemanlar birleştirilirken yapılmaktadır.

             | Steps   |Divided & Merged Schema|
             
             | Start   |        [16,21,11,8,12,22]            |
             | Divide1 |  [16,21,11]     -       [8,12,22]    |
             | Divide2 |[16] - [21,11]   -     [8] - [12,22]  |
             | Divide3 |[16] - [21] - [11] - [8] - [12] - [22]|
             | Merge1  |[16] - [21,11] -   [8] - [12,22]      |
             | Merge2  |   [11,16,21] - [8,12,22]             |
             | Merge3  |        [8,11,12,16,21,22]            |
 
- Big-O gösterimini yazınız.
Big-O &rarr; O(nlogn)= O(6log6) olarak gösterilir.

www.patika.dev