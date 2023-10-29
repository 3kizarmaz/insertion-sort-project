# insertion-sort-project

Merhaba. Bu projede Sorting Algoritmalarından biri olan Insertion Sort için örnekler yapacağız.
Hi. In this project, we will make examples for Insertion Sort, one of the Sorting Algorithms.

[22,27,16,2,18,6] -> Insertion Sort

1) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.(Write the stages of the sequence given above according to sort type.)
2) Big-O gösterimini yazınız.(Write the Big-O notation.)
3) Time Complexitysi hangi türdedir?(worst, avarage, best)(What is the type of Time Complexity (worst, average, best)?)
4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.(Which case does the number 18 fall under after the sequence is sorted? Write it down.)
5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.(Write the first 4 steps of the sequence [7,3,5,8,2,9,4,15,6] according to Insertion Sort.)

Çözüm 1:(Solution 1:)

[22,27,16,2,18,6]n

[2,27,16,22,18,6]n-1

[2,6,16,22,18,27]n-2

[2,6,16,18,22,27]n-3

Çözüm 2:(Solution 2:)
Dizide yapılan işlemler n+(n-1)+(n-2)+...+1 e kadar gideceği için toplamları yazılmalıdır. n.(n+1)/2 den n^2+n/2 sonucu çıkacaktır. Burada, kuvveti en büyük olan fonksiyon alınmalıdır. Çünkü, birim zamanda yapılan işin süresi bu fonksiyona bağlıdır. Bu dizinin Big-O gösterimi O(n^2) dir. (Solution 2: Since the operations performed in the sequence will go up to n+(n-1)+(n-2)+...+1, their sums should be written. n.(n+1)/2 will result in n^2+n/2. Here, the function with the largest power should be taken. Because the duration of the work done per unit time depends on this function. The Big-O representation of this sequence is O(n^2).)

![insertion-sort-graph](https://user-images.githubusercontent.com/28534878/152795690-73c70acf-31bd-4897-a7b6-dc279f2ab380.jpeg)

Çözüm 3:(Solution 3:)
Time complextysi worst case'dir. Çünkü, dizide birim zamanda yapılan işlerin süresi artmaktadır.(Time complexity is the worst case. This is because the duration of the work done per unit time in the sequence increases.)

Çözüm 4:(Solution 4:)
Dizi sıralandıktan sonra 18 sayısı worst case'ye girer. Çünkü, 18 sayısına ulaşmak için birim zamanda yapılan işlemlerin süresi uzundur.(After sorting the sequence, the number 18 enters the worst case. This is because it takes a long time per unit time to reach the number 18.)

Çözüm 5:(Solution 5:)

1.adım:(Step 1:) [7,3,5,8,2,9,4,15,6]n

2.adım:(Step 2:) [2,3,5,8,,7,9,4,15,6]n-1

3.adım:(Step 3:) [2,3,4,8,7,9,5,15,6]n-2

4.adım:(Step 4) [2,3,4,5,7,9,8,15,6]n-3
