# MergeSort

Proje 2:
[16,21,11,8,12,22] 
a- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

b- Big-O gösterimini yazınız.

Cevap:
a- 
  1-[16, 21, 11] _ [8, 12, 22]
  2-[16, 21] [11] _ [8, 12] [22]
  3-[16][21][11] _ [8][12][22]
  4-[16, 21] _ [11, 8] _ [12, 22]
  5-[8, 11, 16, 21] _ [12, 22]
  6-[8, 11, 12, 16, 21, 22]
  
b- 2^x=n >>> logn=x ___ Big O Notation = O(nlogn)
