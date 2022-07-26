# Insertion-Sort 


## Proje 1

### 1. Soru 

**[22,27,16,2,18,6]** -> Insertion Sort

- a) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- b) **Big-O** gösterimini yazınız.
- c)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- d) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### 2. Soru


- a) **[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1.a) Insertion-Sort Aşamaları

##### Aşama 1:

 Verilen dizideki mevcut olan elemanlardan en küçük değer olan ''2'' belirlenir ve en baştaki değer ''22'' ile yer değiştirilir.
 |1.Adım|2|27|16|22|18|6|     
|------|- |- |- |-|- |-|


##### Aşama 2:


İlk aşama tamamlandıktan sonra kalan elemanlar içinde en küçük değer olan ''6'' ve 2. veri olan ''27'' yer değiştirilir.
|2.Adım|2|6 |16|22|18|27|     
|------|- |- |- |-|- |-|

##### Aşama 3:


İlk iki adım tamamlandıktan sonra 2. değerden sonraki elemanlar içinde en küçük eleman ''16''dır. Zaten 3. sıraya yazılması gerektiğinden yerinin değiştirilmesine gerek yoktur.
 |3.Adım|2|6 |16|22|18|27|     
|------|- |- |- |-|- |-|


##### Aşama 4:


4. sıraya yazılacak elemanı belirlemek için kalan elemanlar içerisinde en küçük değer olan ''18'' belirlenir ve 4. sıradaki ''22'' ile yeri değiştirilir.

|4.Adım|2|6|16|18|22|27|     
|------|- |- |- |-|- |-|

##### Aşama 5:

5.sıradaki eleman ''22'' halihazırda ''27'' den küçük olduğundan dolayı kendi sırasında kalır ve aşamalar sıralanmış olur.
|5.Adım|2|6|16|18|22|27|     
|------|- |- |- |-|- |-|


## 1.b) Insertion-Sort Big-O Gösterimi


Big-O notation bir algoritmanın performansını veya time complexity’sini hesaplamak için kullanılır. Insertion-sort dizilerinde verilen veri seti ''n'' elemanlı olduğu düşünüldüğünde ilk aşamada ''n'' eleman incelenir ve en küçük olanı belirlenir. 2. aşamada 2. sıra için kalan elemanlar (n-1) incelenir ve son elemana kadar bu şekilde devam eder. 1'den n'e kadar olan sayıların toplamı *[(n²+n)/2]* şeklinde bulunur. Denklemin domine eden fonksiyonu olan O(n²) bize ınsertion-sort için Big-o gösterimini ifade eder.

Liste 6 elemanlı olduğundan O(62)=36 olacaktır.

## 1.c) Time Complexity

**Average Case**: Aradığımız sayının ortada olmasıdır.

|Average Case|22|27|16|2|18|16|     
|------|- |- |- |-|- |-|

**Worst Case**: Aradığımız sayının sonda olmasıdır.

|Worst Case|27|22|18|16|6|2|     
|------|- |- |- |-|- |-|

**Best Case**: Aradığımız sayının başta olmasıdır.

|Best Case|2|6|16|18|22|27|     
|------|- |- |- |-|- |-|

## 1.d) ''18'' Sayısı'nın Case'i

Dizi sıralandıktan sonra 18 sayısı ortada olacağından **Average Case** kapsamındadır.


## 2) **[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımı

|1.Aşama|2 |3|5|8|7|9|4|15|6|     
|------|- |- |- |-|- |-|-|-|-|
|2.Aşama|2 |3|5|8|7|9|4|15|6|     
|3.Aşama|2 |3|4|8|7|9|5|15|6| 
|4.Aşama|2 |3|4|5|7|9|8|15|6| 

 www.patika.dev
 