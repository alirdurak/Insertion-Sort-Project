## [22,27,16,2,18,6] -> Insertion Sort
- [22,27,16,2,18,6] -----Başlangıç durumu.
- [2,27,16,22,18,6]
- [2,6,16,22,18,27]
- [2,6,16,22,18,27] ----- Üçüncü eleman olması gereken yerde olduğu için dizi aynı kalır.
- [2,6,16,18,22,27]
- [2,6,16,18,22,27] ------Beşinci eleman olması gerekn yerde olmasından dolayı dizi aynı kalır.
- [2,6,16,18,22,27]------- Dizinin son hali budur

##Big O Gösterimi
- n! = n*(n+1)/2) = (n^2+n)/2 => O(n^2)
##Time Complexity
### Worst Case:  O(n^2)
### Average Case: O(n^2)
### Best Case: O(n)

## Dizi sıralandıktan sonra "18" sayısı hangi case kapsamına girer?
- 18 Sayısı dizinin orta kısımlarında kaldığından dolayı Average Case kapsamına girer.

##[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı
[7,3,5,8,2,9,4,15,6]----- Başlangıç durumu.
[2,3,5,8,7,9,4,15,6]----- Birinci adım.
[2,3,5,8,7,9,4,15,6] ----- İkinci adım. İkinci eleman yerinde odluğundan dolayı dizi değişmedi.
[2,3,5,8,7,9,4,15,6]----- Üçüncü adım. Üçüncü eleman yerinde olduğundan dolayı dizi değişmedi.
[2,3,5,7,8,9,4,15,6]------ Dördüncü adım.
 



