Insertion Sort

Insertion sort sıralı diziyi her adımda eleman eleman oluşturan bir sıralama algoritmasıdır. 

Proje 1

[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
-Verilen dizide öncelikle en küçük eleman bulunur.
-Bulunan en küçük elemanı dizinin en başındaki sayı ile değiştiririz.
-Daha sonra 2.en küçük sayı bulunur ve dizinin 2.sayısı ile değiştirilir.
-Dizinin 3. sırasındaki sayı, dizideki en küçük 3.sayı ise o sayı öyle bırakılır ve 4.sayıya geçilir.
-Dizinin sonunda gelene kadar bu algoritma mantığı bu şekilde devam eder.

1.Adım [22,27,16,2,18,6] n
2.Adım [2,27,16,22,18,6] n-1
3.Adım [2,6,16,22,18,27] n-2
4.Adım [2,6,16,18,22,27] 1

2.Big-O gösterimini yazınız.
n! = n * (n+1)/2 = (n^2+n)/2
O(n^2)

3.Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
18 sayısı Average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.Adım [2,3,5,8,7,9,4,15,6]   

2.Adım [2,3,4,8,7,9,5,15,6]

3.Adım [2,3,4,5,7,9,8,15,6]

4.Adım [2,3,4,5,6,9,8,15,7]
