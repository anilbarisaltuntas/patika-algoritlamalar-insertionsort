**[22,27,16,2,18,6]** -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.


Başlangıç dizisi: `[22, 27, 16, 2, 18, 6]`

1. Adım (22|27): 22 ile 27 kıyaslanır. 27 büyük olduğu için yerinde kalır.
    * `[22, 27, 16, 2, 18, 6]`
2. Adım (16): 16 sayısı 27 ve 22 ile kıyaslanır. En küçüktür, en başa gelir.
    * `[16, 22, 27, 2, 18, 6]`
3. Adım (2): 2 sayısı; 27, 22 ve 16 ile kıyaslanır. Hepsinden küçüktür, en başa gelir.
    * `[2, 16, 22, 27, 18, 6]`
4. Adım (18): 18 sayısı; 27 ve 22'den küçük, 16'dan büyüktür. Araya girer.
    * `[2, 16, 18, 22, 27, 6]`
5. Adım (6): 6 sayısı; 27, 22, 18 ve 16'dan küçük, 2'den büyüktür. 2'nin sağına girer.
    * `[2, 6, 16, 18, 22, 27]`

---

Algoritmanın en kötü senaryodaki (Worst Case) çalışma zamanı:
**O(n^2)**


Sıralı dizi: `[2, 6, 16, 18, 22, 27]`

Aradığımız sayı dizinin tam ortasında yer almaktadır. Bu nedenle Avarage Case kapsamına girer.

**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. Adım: [2,3,5,8,7,9,4,15,6]
2. Adım: [2,3,5,8,7,9,4,15,6]
3. Adım: [2,3,4,8,7,9,5,15,6]
4. Adım: [2,3,4,5,7,9,8,15,6]
