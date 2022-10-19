[Patika.Dev](www.patika.dev)

### Proje 3
### 1) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. (Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.)
	- [7,5,1,8,3,6,0,9,4,2] (root = 6)




|             |  |  |  |  |  |  |     |  |  |  |  |   |   |
|--           |--|--|- |- |- |- |-    |- |- |- |- |-  |-  |
|             |  |  |  |  |  |  | 7   |  |  |  |  |   |   |
|             |  |  |  |  |  | /|     |\ |  |  |  |   |   |
|             |  |  |  |  | 5|  |     |  |8 |  |  |   |   |
|             |  |  |  | /|  |\ |     |  |  |\ |  |   |   |
|             |  |  | 1|  |  |  |6    |  |  |  |9 |   |   |
|             |  | /|  |\ |  |  |     |  |  |  |  |   |   |
|             | 0|  |  |  |3 |  |     |  |  |  |  |   |   |
|             |  |  |  | /|  |\ |     |  |  |  |  |   |   |
|             |  |  | 2|  |  |  |4    |  |  |  |  |   |   |
|             |  |  |  |  |  |  |     |  |  |  |  |   |   |

	Basamaklar
		1) 7 Root olarak seçildi.
		2) 5, 7'den küçük sola yerleştirildi.
		3) 1, 7'den ve 5'ten küçük, 5'in soluna yerleştirildi.
		4) 8, 7'den büyük sağa yerleştirildi.
		5) 3, 7'den ve 5'den küçük, 1'den büyük olduğundan 1'in sağına yerleştirildi.
		6) 6, 7'den küçük ancak 5'den büyük olduğundan 5'in sağına yerleştirildi.
		7) 0, en küçük sayı olduğundan 1'in soluna yerleştirildi.
		8) 9, en büyük sayı olduğundan 8'in sağına yerleştirildi.
		9) 4, 7'den ve 5'ten küçük ama 1'den ve 3'ten büyük olduğundan 3'ün sağına yerleştirildi.
		10) 2, 7'den ve 5'ten küçük, 1'den büyük ancak 3'ten küçük. Bu nedenle 3'ün soluna yerleştirildi.
