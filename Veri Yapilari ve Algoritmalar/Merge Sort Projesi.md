# Merge Sort Projesi

1- [16,21,11,8,12,22]** -> Merge Sort

A) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
B) Big-O gösterimini yazınız.


# 1
## A

```
   [16,21,11,8,12,22]
            /   \
    [16,21,11]   [8,12,22]
       / \        	 / \
    [16,21][11]  [8,12][22]
      / \   |       / \   | 
   [16][21][11]   [8][12][22]
     |   \ /      |   \ /
    [16][11,21]  [8][12,22]
      \  /        \  /
     [11,16,21][8,12,22]
            \  /
      [8,11,12,16,21,22]
```

## B
 Big O  =  O(nlogn)

