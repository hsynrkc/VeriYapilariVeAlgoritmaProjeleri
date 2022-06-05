Merge Sort

Girdi olarak aldığı diziyi en küçük hale gelene kadar ikili gruplara böler ve karşılaştırma yöntemi kullanarak diziyi sıralama algoritmasıdır.

Proje 2
[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

             [16,21,11,8,12,22] 

  [16,21,11]                    [8,12,22] 

 [16]  [21,11]                 [8,12]   [22] 

 [16]   [21] [11]              [8] [12]   [22] 

 [16]   [11,21]					[8,12]  [22]

   [16,21,11]                    [8,12,22] 

             [8,12,16,21,11,22]


2.Big-O gösterimini yazınız.

2^x=n => logn

O(nlogn)'dir