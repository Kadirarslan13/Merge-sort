## [16,21,11,8,12,22] -> Merge Sort

a) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
b) Big-O gösterimini yazınız.

### Cevap 

 a)

* [16,21,11] [8,12,22]
* 16 [21,11] 8 [12,22]
* 16 21 11   8 12 22
* 16 [11,21] 8 [12,22]
* [11,16,21] [8,12,22]
* [8,11,12,16,21,22]

---

b)

* ikiye bölerek ilerlediği için 2^x=n'den x=log(n) dir time complexity O(n) olduğu için O(nlogn)dir 

[patika](https://www.patika.dev)
