# Veri Yapıları ve Algoritmalar

------------


## Merge Sort Projesi
Bir listeyi her adımda iki parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor (Performans).

### Proje 2

**[16,21,11,8,12,22]** -> Merge Sort

**1-** Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
**2-** Big-O gösterimini yazınız.


------------

##### Çözüm :

**1. Merge Sort aşamaları ;**

***Adım 1  >>* **      [16,21,11,8,12,22]
***Adım 2  >>* **      [16,21,11]    [8,12,22]   **not: ** iki parçaya böldük.
***Adım 3  >>* **      [16,21]  [11]    [8]  [12,22]   **not: ** ikiye böldüğümüzün her birini tekrar ikiye böldük.Tek sayılı elemana sahipse tam ortadan olmayacaktır.Önemli değil!!
***Adım 4  >>* **      [16]  [21]  [11]    [8]  [12]  [22]   **not: ** ikiye bölmeye devam ediyoruz ve bu adımda herbiri tek elemanlıya döndü.Şimdi birleştiriyoruz.Birleştirirken sıralı olarak yapıyoruz.
***Adım 5  >>* **      [16]  [11,21]    [8]  [12,22]  
***Adım 6  >>* **      [11,16,21]        [8,12,22]   **not: ** sıralı birleştirmeye devam ediyoruz.
***Adım 7  >>* **      [8,11,12,16,21,22]   **not: ** ve sıralı şeklilde bitti.

**2. Big-O Gösterimi  ;**

Her birleştirme işleminde sıralı birleştirdiğimiz için her zaman soldaki elemanlar küçük olan sayı olacaktır. Dolayısıyla birleştirme işlemine devam ederken sadece soldaki elemanları karşılaştırıp küçük olanını yeni kümeye ekliyoruz. Ve karşılaştırdığımız elemanla işimiz bittiği için sonraki aşamada toplam işlem sayısından 1 işlem az  yapmış oluyoruz. Yani her seferinde yaptığımız işlem sayısını n kabul edersek bir sonraki adımda n-1 olacaktır. Ve her adımda n-1 işlem yapmaya devam ederiz. Time Complexity'si n-1 ve dominant faktörü ise n olmuş oluyor. O zaman her seferinde yarıya inerek devam ettiği için;  2^x = n  >  logn = x  >    **O(nlogn)**     olur.
