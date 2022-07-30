# Proje 1

**[22,27,16,2,18,6]** -> Insertion Sort
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
<br></br>
**[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
<br></br>
---
<br></br>
##1 Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- **1. çevrim**
<br></br>
    1. ![1. aşama](https://raw.githubusercontent.com/qutaiba-963/Kodluyoruz_Proje1/main/resimler/1.jpg)
<br></br>
<br></br>
- **2. çevrim**
<br></br>
    1. ![1. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/2.1.jpg)
<br></br>
    2. ![2. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/2.2.jpg)
<br></br>
    3. ![3. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/2.3.jpg)
<br></br>
<br></br>
- **3. çevrim**
<br></br>
    1. ![1. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/3.1.jpg)
<br></br>
    2. ![2. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/3.2.jpg)
<br></br>
    3. ![3. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/3.3.jpg)
<br></br>
    4. ![4. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/3.4.jpg)
<br></br>
<br></br>
- **4. çevrim**
<br></br>
    1. ![1. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/4.1.jpg)
<br></br>
    2. ![2. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/4.2.jpg)
<br></br>
    3. ![3. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/4.3.jpg)
<br></br>
<br></br>
- **5. çevrim**
<br></br>
    1. ![1. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/5.1.jpg)
<br></br>
    2. ![2. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/5.2.jpg)
<br></br>
    3. ![3. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/5.3.jpg)
<br></br>
    4. ![4. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/5.4.jpg)
<br></br>
    5. ![5. aşama](https://github.com/qutaiba-963/Kodluyoruz_Proje1/raw/main/resimler/5.5.jpg)

----
<br></br>
##2 Big-O gösterimini yazınız.
**[22,27,16,2,18,6]** dizisinin Insertion Sort yapılması için dizinin her bir elemanı diğer tüm elemanlarla karşılaştırılması gerekir, yani dizi gezilen her elemanı için gözden geçirilmesi gerekir bu durumda da iç içe döngü kullanılması bir çözümdür o yüzden de Big O notation'o O(n^2) olur.


----
<br></br>
##3 Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

1. Worst Case : **O(n^2)**
2. Average Case : **O(n^2)**
3. Best Case (dizi sıralı ise): **O(n)** 
----
<br></br>
##4 Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Dizi sıralandıktan sonra 18 sayısı Average Case kapsamına girer.



----
<br></br>
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```javascript
insertionSort([7,3,5,8,2,9,4,15,6])
```

- **1. çevrimde** `arr[1] = 3` dolayısıyla  `temp = 3` `j` ise `i-1` olduğu için `j=0 = arr[0]` ve değeride **7**, `while`'ın ilk koşulu **0**'dan büyük eşitse sağlanıyor ve **7 3**'den büyük olduğu için `while` döngüsüne giriyor ve **3** ile **7** yer değiştiriyor. **j** bir azaltılıyor ve -1 olduğu için while döngüsüne girilmiyor ve 2. çevrime geçiliyor.
**[3,7,5,8,2,9,4,15,6]**
 <br></br>
- **2. çevrimde** `arr[2] = 5` dolayısıyla  `temp = 5` `j` ise `i-1` olduğu için `j=1 = arr[1]` ve değeride **7**, `while`'ın ilk koşulu **0'dan büyük eşitse** sağlanıyor **7 5**'den büyük olduğu içinde koşullar sağlandığı için `while` döngüsüne giriliyor ve **7 ile 5**'in yeri değişiyor daha sonra `j` **1** azaltılıyor ve değeri  `j=0` oluyor.
**[3,5,7,8,2,9,4,15,6]**
<br></br>
- `j=0` olduğu için ve **3** **5**'den büyük olmadığı için `while` döngüsüne girilmiyor ve 3. çevirme geçiliyor.
<br></br>
- **3. çevrimde** `arr[3] = 8` dolayısıyla  `temp = 8` `j` ise `i-1` olduğu için `j=2 = arr[2]` ve değeride **7**, `while`'ın ilk koşulu **0**'dan büyük eşitse sağlanıyor **7** **8**'den büyük olmadığı için `while` döngüsünde çıkılıyor.
**[3,5,7,8,2,9,4,15,6]**
<br></br>
- **4. çevrimde** `arr[4] = 2` dolayısıyla  `temp = 2` `j` ise `i-1` olduğu için `j=3 = arr[3]` ve değeride **8**, `while`'ın ilk koşulu **0**'dan büyük eşitse sağlanıyor **2** **8**'den büyük olduğu için `while` döngüsünde giriliyor ve **2** ile **8** yer değiştiriyor ve j 1 azaltılıyor.
**[3,5,7,2,8,9,4,15,6]**
<br></br>
`j=2` olduğu için `while` döngüsü 2'yi en başa alana kadar  tekrar çalışıyor.
**[2,3,5,7,8,9,4,15,6]**