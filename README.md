# InsertionSortProject

### Soru-1
[22,27,16,2,18,6]
Yukarı verilen dizinin selection sort türüne göre aşamalarını yazınız.
```
İlk aşama dizinin en küçük elemanı olan 2 sayısı ile dizinin ilk elemanının yer değiştirmesi
[2,27,16,22,18,6]
İkinci aşama ikinci en küçük sayı olan 6 ile dizinin ikinci elemanının yer değiştirmesi
[2,6,16,22,18,27]
Üçüncü kontrol edilen sayı olan 16 dizide doğru yerde olduğu için dördüncü sıraya geçilir ve 18 sayısı ile dizinin dördüncü elemanı yer değiştirilir.
[2,6,16,18,22,27]
```
Big-O gösterimini yazınız.
```
Her elemanı sırası ile tek tek kontrol ettiği için
n + (n-1) + (n-2) + ... + 1 = n*(n-1)/2
-> O(n^2) olur.
```

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız


Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
```
Dizi sıralandıktan sonra 18 sayısı ortaya geleceğinden Time Complexity'si Average Case olur.
```
### Soru-2

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
```