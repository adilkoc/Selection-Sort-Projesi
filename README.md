Veri Yapıları ve Algoritmalar
Selection Sort Project
[22,27,16,2,18,6] -> Insertion Sort
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6]
n tane işlem yapıldı yani ne kadar sayı varsa

[2,27,16,22,18,6]
(n-1) tane işlem yapıldı çünkü ilkine bakmadı ilki zaten en küçük

[2,6,16,22,18,27]
(n-2) tane işlem yapıldı çünkü ilk ikisi zaten sıralıydı

[2,6,16,18,22,27]
(n-3) tane işlem yapıldı ilk üçü sıralı olduğu için ve sıralama bitti

Big-O gösterimini yazınız.
n + (n-1) + (n-2) + (n-3) + 1 = n.(n+1) / 2 = n^2+1/2 = O (n^2)

Time Complexity:
18 olan aradığımız sayının ortaya yakın olması sebebiyle cevap Average case olmalıdır.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6]
En küçüğü bulmak için n tane işlem yapar sayı kadar

[2,3,5,8,7,9,4,15,6]
(n-2) tane işlem yapar en küçük iki tane başta olduğundan

[2,3,4,8,7,9,5,15,6]
(n-3) tane işlem yapar en küçük üç tane başta olduğundan

[2,3,4,5,7,9,8,15,6]
(n-4) tane işlem yapar en küçük dört tane başta olduğundan . . .
