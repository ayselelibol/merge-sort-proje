# Merge Sort

```
                    [16,21,11,8,12,22]
      [16,21,11]                         [8,12,22]
    [16]    [21,11]                    [8,12]  [22]
[16]      [21]  [11]                 [8]  [12]  [22]
[16]         [11,21]                  [8,12]     [22]
    [11,16,21]                          [8,12,22]
                    [8,11,12,16,21,22]
```
#### Big-O gösterimi 
```
n tane aşama vardır
her aşamada yarıya iner bu yüzden 2^x=n
logn=x
o(nlogn)
```




