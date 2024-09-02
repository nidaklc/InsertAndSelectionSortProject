## InsertAndSelectionSortProject
  [22,27,16,2,18,6] -> Insertion Sort Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
      
      [22,27,16,2,18,6]  22 ve 27 doğru sırada.
      [16,22,27,2,18,6]  27 ve 16 sayıları karşılaştırılır. 16 daha küçük olduğu için yer değiştirirler. 16, 22'den de küçük olduğu için onunla da yer değiştirir.
      [2,16,22,27,18,6]  2 diğerlerinden en küçük olduğundan en başa gelir.
      [2,16,18,22,27,6]  Aynı şekilde sıralanmaya devam eder.
      [2,6,16,18,22,27]
      
  Big-O gösterimini yazınız. 
      
      
      Her eleman, dizinin diğer elemanlarıyla karşılaştırılıyor bu yüzden dizinin ortalama veen kötü koşulda çalışması O(n^2) olarak ifade edilir. 
   Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız  
   Average case: Aradığımız sayının ortada olması
   Worst case: Aradığımız sayının sonda olması
   Best case: Aradığımız sayının dizinin en başında olması.
         
      Dizinin son hali [2,6,16,18,22,27] şeklindedir. Yani avarage case durumundadır.
  [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

       [2,3,5,8,7,9,4,15,6]   Dizinin en küçük elemanı 0. index'e getirilir, sonrasında 1. index yerine konulacak en küçük sayı belirlenir.
       [2,3,5,8,7,9,4,15,6]   Yukarıdaki işlem devam eder ta ki bütün sayılar küçükten büyüğe sıralanmış olana dek
       [2,3,4,8,7,9,5,15,6]
       [2,3,4,5,7,9,8,15,6]
       
      
              


  
<!---
nidaklc/nidaklc is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
