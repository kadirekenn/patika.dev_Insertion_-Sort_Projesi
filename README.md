# patika.dev_Insertion_-Sort_Projesi

[Patika.dev](https://www.patika.dev/tr)

[22,27,16,2,18,6] -> Insertion ort

1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.
3)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

1) [22,27,16,2,18,6] ilk önce en küçük elemanın 2 olduğunu bulduk onu 22 ile yer değiştirerek en başa aldık,
   [2,27,16,22,18,6] sonraki sayımız 6, 27 ile yer değiştirdik,
   [2,6,16,22,18,27] sıradaki sayımız 16 olduğu için devam ediyoruz, 18'e geliyoruz, 22 ile yer değiştiriyoruz,
   [2,6,16,18,22,27] daha sonra 22 ve 27'ye bakıyoruz ve sıralama tamamlanmış oluyor.
   
2)Big-O gösterimi : Q(n^2)
3)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4)Aradığımız sayı (18) en başta veya en sonda olmadığından Average case kapsamına girer.



[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6] 
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
