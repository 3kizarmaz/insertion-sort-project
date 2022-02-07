# insertion-sort-project

Merhaba. Bu projede Sorting Algoritmalarından biri olan Insertion Sort için örnekler yapacağız.

[22,27,16,2,18,6] -> Insertion Sort

1) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2) Big-O gösterimini yazınız.
3) Time Complexitysi hangi türdedir?(worst, avarage, best)
4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Çözüm 1:

[22,27,16,2,18,6]n

[2,27,16,22,18,6]n-1

[2,6,16,22,18,27]n-2

[2,6,16,18,22,27]n-3

Çözüm 2:
Dizide yapılan işlemler n+(n-1)+(n-2)+...+1 e kadar gideceği için toplamları yazılmalıdır. n.(n+1)/2 den n^2+n/2 sonucu çıkacaktır. Burada, kuvveti en büyük olan fonksiyon alınmalıdır. Çünkü, birim zamanda yapılan işin süresi bu fonksiyona bağlıdır. Bu dizinin Big-O gösterimi O(n^2) dir. 

![insertion-sort-graph](https://user-images.githubusercontent.com/28534878/152795690-73c70acf-31bd-4897-a7b6-dc279f2ab380.jpeg)

Çözüm 3:
Time complextysi worst case'dir. Çünkü, dizide birim zamanda yapılan işlerin süresi artmaktadır.

Çözüm 4:
Dizi sıralandıktan sonra 18 sayısı worst case'ye girer. Çünkü, 18 sayısına ulaşmak için birim zamanda yapılan işlemlerin süresi uzundur.

Çözüm 5:

1.adım: [7,3,5,8,2,9,4,15,6]n

2.adım: [2,3,5,8,,7,9,4,15,6]n-1

3.adım: [2,3,4,8,7,9,5,15,6]n-2

4.adım: [2,3,4,5,7,9,8,15,6]n-3
