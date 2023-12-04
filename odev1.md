Project 1 Selection Sort Projesi

- [22, 27, 16, 2, 18, 6] -> Insertion Sort
Yukarıda gösterilen dizinin sort türüne göre aşamalarını yazın. Big-O gösterimini yazın.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case' lerden hangisinin kapsamına girer yazınız.

Average Case: Aradığımız sayının ortada olması
Worst Case: Aradığımız sayının sonda olması
Best Case: Aradığımız sayının en başlarda olması

* Çözüm:

- [22, 27, 16, 2, 18, 6] -> En küçüğüne bakılır, en küçüğü 2, baştaki 22 ile yer değiştir. -> n
- [2, 27, 16, 22, 18, 6] -> 2 en başta ve hariç tutulacak şekilde en küçüğüne bak, en küçüğü 6, baştaki 27 ile yer değiştir. -> n-1
- [2, 6, 16, 22, 18, 27] -> 2 ve 6 en başta ve hariç tutulacak şekilde en küçüğüne bak, en küçüğü 16, en başta yer aldığı için yer değişikliğine gerek yok. ->n-2
- [2, 6, 16, 22, 18, 27] -> 2, 6 ve 16 en başta ve hariç tutulacak şekilde en küçüğüne bak, en küçüğü 18, baştaki 22 ile yer değiştir. -> n-3
- [2, 6, 16, 18, 22, 27] -> 2, 6, 16 ve 18 en başta ve hariç tutulacak şekilde en küçüğüne bak, en küçüğü 22, en başta yer aldığı için yer değişikliğine gerek yok. -> n-4
- [2, 6, 16, 18, 22, 27] -> Dizinin en son hali bu sekilde olmalidir. -> 1

* Big-O Notation:
n + (n-1) + (n-2) + (n-3) + (n-4) + 1 -----> (n * (n+1)) / 2 -----> (n^2) * n / 2 -----> O(n^2)

Time Complexity: Middle 

---

[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort' a göre ilk dört adımını yazınız:

Çözüm:
- Başlangıç -> [7, 3, 5, 8, 2, 9, 4, 15, 6] -> İlk önce elemanlar sıralandı.

- Adım 1 -> [2, 3, 5, 8, 7, 9, 4, 15, 6] -> "2" bir işlem yapılmadı, en küçük eleman 3, en başta bulunduğu için yer değiştirmedi.
- Adım 2 -> [2, 3, 4, 8, 7, 9, 5, 15, 6] -> "2 & 3" bir işlem yapılmadı, en küçük eleman 4, en baştaki 5 ile yer değiştirdi
- Adım 3 -> [2, 3, 4, 8, 7, 9, 5, 15, 6] -> "2, 3 ve 4" bir işlem yapılmadı, en küçük eleman 5, en baştaki 8 ile yer değiştirdi.
- Adım 4 -> [2, 3, 4, 5, 6, 9, 8, 15, 7] -> "2, 3, 4 ve 5" bir işlem yapılmadı, en küçük eleman 6, en baştaki 7 ile yer değiştirdi.
- Adım 5 -> [2, 3, 4, 5, 6, 7, 8, 15, 9] -> "2, 3, 4, 5 ve 6" bir işlem yapılmadı, en küçük eleman 7, en baştaki 9 ile yer değiştirdi.
- Adım 6 -> [2, 3, 4, 5, 6, 7, 8, 15, 9] -> "2, 3, 4, 5, 6 ve 7" bir işlem yapılmadı, en küçük eleman 8, en başta bulunduğu için yer değiştirmedi.
- Adım 7 -> [2, 3, 4, 5, 6, 7, 8, 9, 15] -> "2, 3, 4, 5, 6, 7 ve 8" bir işlem yapılmadı, en küçük eleman 9, en başta bulunan 15 ile yer değiştirdi ve aşağıdaki gibi oldu.

- Son -> [2, 3, 4, 5, 6, 7, 8, 9, 15] -> Tüm elemanlar sıralanmış halde, dizinin son hali bu şekildedir.




--- 

- Proje 2 Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

- [16,21,11,8,12,22]
- [16,21,11] [8,12,22]
- [16,21] [11] - [8,12] [22]
- [16] [21] [11] - [8] [12] [22]
- [16,21] [8,11] [12,22]
- [8,11,12,16,21,22]


- Proje 3 Binary Search Tree Projesi

- Adım 1: 1<5 için Root' un solunda 1
- Adım 2: 7>5 için Root' un sağında 7
- Adım 3: 0<1 ve 0<5 için Root' un solunda 0
- Adım 4: 3>1 ve 3<5 için Root' un sağında 3
- Adım 5: 2<3, 2>1 ve 2<5 için Root' un solunda 2
- Adım 6: 4>3, 4>1 ve 4<5 için Root' un sağında 4
- Adım 7: 6<7 ve 6>5 için Root' un solunda 6
- Adım 8: 9>7 ve 9>5 için Root' un sağında 9
- Adım 9: 8<9 ve 8>5 için Root' un solunda 8