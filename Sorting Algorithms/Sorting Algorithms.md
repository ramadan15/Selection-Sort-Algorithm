# Proje 1 (Selection Sort)
- [22,27,16,2,18,6] veri dizisinin selection sort türüne göre sıralayacak olursak:
- En küçük eleman bulunana kadar dizideki tüm elemanlar aranır. 
- Bulunan en küçük eleman dizinin başına eklenir. 
- Her adım da eleman sayısı azalacağından adım sayısı azaları. 
- 1.Adım:
 [*2*,22,27,16,18,6]
- 2.Adım
 [*2*,*6*,22,27,16,18]
 - 3.Adım
 [*2*,*6*,*16*,22,27,18]
 - 4.Adım
 [*2*,*6*,*16*,*18*,22,27]
 - 5.Adım
 [*2*,*6*,*16*,*18*,*22*,27]
 - 6.Adım
 [*2*,*6,*16*,*18*,*22*,*27*]
 
 - Her adımda gidilen eleman sayısı birer azalacağından Benim toplam adım sayım (big o'notation): (n.(n+1))/2

 - Time complexity hesabında ise en yüksek değeri olan eleman değerlendirileceğinden:

 Bu algoritmanın time complexity: n^2 olarak değerlendirilmektedir. 
 