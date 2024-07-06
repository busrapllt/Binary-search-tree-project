# Binary-search-tree-project
Binary search tree project
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root: İlk eleman 7'dir.
5 elemanı 7'den küçüktür, bu yüzden 7'nin soluna eklenir.
1 elemanı 7'den ve 5'ten küçüktür, bu yüzden 5'in soluna eklenir.
8 elemanı 7'den büyüktür, bu yüzden 7'nin sağına eklenir.
3 elemanı 7'den ve 5'ten küçüktür, ama 1'den büyüktür, bu yüzden 1'in sağına eklenir.
6 elemanı 7'den küçüktür, ama 5'ten büyüktür, bu yüzden 5'in sağına eklenir.
0 elemanı 7'den, 5'ten ve 1'den küçüktür, bu yüzden 1'in soluna eklenir.
9 elemanı 7'den ve 8'den büyüktür, bu yüzden 8'in sağına eklenir.
4 elemanı 7'den ve 5'ten küçüktür, ama 3'ten büyüktür, bu yüzden 3'ün sağına eklenir.
2 elemanı 7'den, 5'ten ve 3'ten küçüktür, ama 1'den büyüktür, bu yüzden 3'ün soluna eklenir.

  7
 / \
5   8
/ \   \
1   6   9
/ \
0   3
/ \
2   4

Bu şekilde, verilen diziye göre oluşturulmuş olan Binary Search Tree'nin son hali görsel olarak yukarıda gösterilmiştir.
