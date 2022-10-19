[Patika.Dev](www.patika.dev)

### Proje 3
### 1) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. (Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.)
	- [7,5,1,8,3,6,0,9,4,2] (root = 6)




|             |  |  |  |  |  |  |     |  |  |  |  |   |   |
|--           |--|--|- |- |- |- |-    |- |- |- |- |-  |-  |
|             |  |  |  |  |  |  | 6   |  |  |  |  |   |   |
|             |  |  |  |  |  | /|     |\ |  |  |  |   |   |
|             |  |  |  |  | 5|  |     |  |7 |  |  |   |   |
|             |  |  |  | /|  |  |     |  |  |\ |  |   |   |
|             |  |  | 1|  |  |  |     |  |  |  |8 |   |   |
|             |  | /|  |\ |  |  |     |  |  |  |  |\  |   |
|             | 0|  |  |  |3 |  |     |  |  |  |  |   |9  |
|             |  |  |  | /|  |\ |     |  |  |  |  |   |   |
|             |  |  | 2|  |  |  |4    |  |  |  |  |   |   |
|             |  |  |  |  |  |  |     |  |  |  |  |   |   |

**Basamaklar**
	1) 6 Root olarak seçildi.
	2) 7, 6'dan büyük sağa yerleştirildi.
	3) 5, 6'dan küçük sola yerleştirildi.
	4) 1, 6'dan ve 5'ten küçük, 5'in soluna yerleştirildi.
	5) 8, 6'dan ve 7'den büyük, 7'nin sağına yerleştirildi.
	6) 3, 6'dan ve 5'den küçük, 1'den büyük olduğundan 1'in sağına yerleştirildi.
	7) 0, en küçük sayı olduğundan 1'in soluna yerleştirildi.
	8) 9, en büyük sayı olduğundan 8'in sağına yerleştirildi.
	9) 4, 6'dan ve 5'ten küçük ama 1'den ve 3'ten büyük olduğundan 3'ün sağına yerleştirildi.
	10) 2, 6'dan ve 5'ten küçük, 1'den büyük ancak 3'ten küçük. Bu nedenle 3'ün soluna yerleştirildi.
