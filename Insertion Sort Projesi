# Veri Yapıları ve Algoritmalar > Insertion Sort Projesi

###### Proje 1
**[22,27,16,2,18,6]** -> Insertion Sort

**1.** Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
**2. **Big-O gösterimini yazınız.
**3.** Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
**4.** Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
**5.** [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

**Çözüm:**

------------

 
**1. Insertion Sort ;  **

[22,27,16,2,18,6] -> Insertion Sort

[16,27,22,2,18,6] —> n

[2,22,27,16,18,6] —> n-1

[2,16,27,22,18,6] —> n-2

[2,6,27,22,18,16] —> n-3					    	 

[2,6,22,27,18,16] —> n-4	

[2,6,18,27,22,16] —> n-5						                 

[2,6,16,27,22,18] —> n-6						                

[2,6,16,22,27,18] —> n-7						   (Big-O gösterimi)  = O (n²) 
[2,6,16,18,27,22] —> n-8

[2,6,16,18,22,27] —> 1

**1. Big-O gösterimi ;**

n + (n-1) + (n-2) + …… (n-8) + 1 = n.(n+1) / 2  = n² + n / 2
( domine eden n² olduğundan onu alıyoruz.)= n² 
(Big-O gösterimi)  = O (n²)

**3. Time Complexity  ; **        Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

 **Worst case:** O (n²)   			      .    **Average case: **O (n²) 
 **Best case:** O (n) 
 
**4. dizi sıralandıktan sonra ;  **

Average case: Aradığımız sayının ortada olması açıklamasına göre  18 sayısı bu kapsama girer.

**5. [7,3,5,8,2,9,4,15,6] dizisi  ;**

[7,3,5,8,2,9,4,15,6]   >   
        1.adım =  [2,3,5,8,7,9,4,15,6]
        2.adım  =  [2,3,5,8,7,9,4,15,6]
        3.adım  =  [2,3,4,8,7,9,5,15,6] 
        4.adım  =  [2,3,4,5,7,9,8,15,6]
