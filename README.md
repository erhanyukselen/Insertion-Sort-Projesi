www.patika.dev
# Insertion-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

[22,27,16,2,18,6]

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

Big-O gösterimi : O(n^2)

TIME COMPLEXITY: Worst Case: O(n^2) Avarage Case : O(n^2) Best Case : O(n)

18 sayısı ortada olduğu için avarage case kapsamına girer.

[7,3,5,8,2,9,4,15,6] 

[2,3,5,8,7,9,4,15,6] - 1

[2,3,4,8,7,9,5,15,6] - 2

[2,3,4,5,7,9,8,15,6] - 3

[2,3,4,5,6,9,8,15,7] - 4


# Merge-Sort-Projesi

 [16,21,11,8,12,22]-Merge Sort
1. aşama: 2 obek şeklinde ayrılır.
(16,21,11) ve (8,12,22)
2. aşama: Tekrar 2 obek şeklinde ayrılır.
(16), (21,11)  ve   (8,12), (22)
3. aşama: Tekrar ayrılır. Sonuç tekli olana kadar.
(16), (21), (11)   ve   (8) ,(12), (22)
4. aşama: sıralama yapılır. 2 şerli gruplar halinde.
(16,21), (11)   ve   (8,12) , (22)
5. aşama: 2 şerli gruplar kendi içinde sıralanır.
(11,16,21)  ve  (8,12,22)
6. aşama: En son oluşan grupların içindeki sayılar kendi içinde sıralanır.
En küçükler arasında karşılaştırılır. 
(8,11,12,16,21,22)

Big-O gösterimi : O(n.logn)
