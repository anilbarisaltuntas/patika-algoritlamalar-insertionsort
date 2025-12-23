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


**Proje 2**

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

16, 21, 11, 8, 12, 22]

[16, 21, 11] ve [8, 12, 22]

[16], [21, 11]

[21], [11] → [11, 21]

[16] + [11, 21] → [11, 16, 21]

[8], [12, 22]

[12], [22] → [12, 22]

[8] + [12, 22] → [8, 12, 22]

[11, 16, 21] + [8, 12, 22] → [8, 11, 12, 16, 21, 22]

**O(nlogN)**

**Binary Search Tree**


1.  **7:** Root (Kök) olarak belirlenir.
2.  **5:** 7'den küçüktür. -> 7'nin soluna eklenir.
3.  **1:** 7'den ve 5'ten küçüktür. -> 5'in soluna eklenir.
4.  **8:** 7'den büyüktür. -> 7'nin sağına eklenir.
5.  **3:** 7'den ve 5'ten küçük, 1'den büyüktür. -> 1'in sağına eklenir.
6.  **6:** 7'den küçük, 5'ten büyüktür. -> 5'in sağına eklenir.
7.  **0:** 7, 5 ve 1'den küçüktür. -> 1'in soluna eklenir.
8.  **9:** 7 ve 8'den büyüktür. -> 8'in sağına eklenir.
9.  **4:** 7 ve 5'ten küçük, 1 ve 3'ten büyüktür. -> 3'ün sağına eklenir.
10. **2:** 7 ve 5'ten küçük, 1'den büyük, 3'ten küçüktür. -> 3'ün soluna eklenir.
