
# Merge Sort Project
Patika.dev Profile: https://app.patika.dev/egementasdemir

## Project: Merge Sort Project (Task Description)
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

---

### 1. [16,21,11,8,12,22] dizisinin sort türüne göre aşamalarını yazınız. ###
> Merge Sort algoritmalarındaki temel mantık diziyi en küçük parçaya bölerek sıralamaktır. Performans açısından Insertion Sort'a göre daha iyidir.

```
1.Adım :      [16,21,11,8,12,22]
2.Adım :    [16,21,11] • [8,12,22]
3.Adım :  [16,21] • 11 • 8 • [12,22]
4.Adım :  16 • 21 • 11 • 8 • 12 • 22
5.Adım :  [16,21] • 11 • 8 • [12,22]
6.Adım :    [11,16,21] • [8,12,22]
7.Adım :      [8,11,12,16,21,22]
```

### 2. BIG-O gösterimini yapınız. ###
```
n(eleman sayısı)=6
Best case    : O(nlogn)
Average case : O(nlogn)
Worst case   : O(nlogn) -> O(6log6)
```
