[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


Merge sort : Merge sort algortimasında verilen dizi tek parça olana kadar dizinin ortanca indeksinden ikiye bölünür. 
İkinci aşamada her bir sayı baştan itibaren kıyaslanarak küçükten büyüğe veya verilen komutlara göre büyükten küçüğe göre yine parça parça sıralanır.
Ve yolun sonunda sıralı bir dizimiz olur .

- [16,21,11,8,12,22] 
- 1-)Dizi 6 elemanlı olduğu için 3 tane olacak şekilde 2 parçaya bölünür.
 -  [16,21,11]  [8,12,22]  
 -2-)Şimdi tekrar ikişer parçaya bölünür      
 -  [16]  [21,11]    [8]  [12,22]    
 -3-)Son kez tek parça kalacak şekilde bölünür.  
 -  [16]   [21] [11]    [8]  [12] [22] 
 -4-)Bu aşamadan sonra birleştirme aşamasına geçilir.
 -  [16]    [11,21]   [8]    [12,22]
 -5-)Teker teker kontrol edilerek birleştirilir.
 -  [11,16,21]    [8,12,22]        
 -6-)Dizi tamamen sıralı bir hale getirilir.
 -  [8,11,12,16,21,22]

Big-O gösterimi : O(logn)
