# **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary Search Tree**
# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

# Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Dizinin en başındaki eleman root olarak seçilir, bu projedeki root 7'dir.

* 5, 7'den küçük olduğu için 7'nin soluna gelir.
* 1, 7'den küçük olduğu için 7'nin soluna gelir.5'ten küçük olduğu için yeni bir bağ ile sol tarafa yazılır.
* 8, 7'den büyük olduğu için 7'nin sağına yazılır.
* 3, 7'den küçük olduğu için sola, 5'ten küçük olduğu için sola, 1'den büyük olduğu için yeni bir bağ ile sağa getirilir.
* 6, 7'den küçük olduğu sola, 5'den büyük olduğu için yeni bir bağ ile sağ tarafa yazılır.
* 0, 7'den küçük olduğu için sola, sırasıyla 1'e kadar gelir. 1'den küçük olduğu için sol tarafa yerleştirilir.
* 9, 7'den büyük olduğu için sağa, 8'den büyük olduğu için onun sağına yazılır.
* 4, 7'den küçük olduğu için sola gelir ve 3'ün sağına yazılır.
* 2, 7'den küçük olduğu için sola, 3 elemanının soluna yazılır.

![BinarySearchTreeImg](img/BinarySearchTreeProject.PNG)

[Patika.dev](https://www.patika.dev) 



