# Sort Projects

## **Proje 1**

[22,27,16,2,18,6] -> **Insertion Sort**

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

```
* [22,27,16,2,18,6]
* [2,27,16,22,18,6]
* [2,6,16,22,18,27]
* [2,6,16,18,22,27]
```

2. Big-O gösterimini yazınız.

```
n+(n-1)+(n-2)+(n-3)+...+1
= n * (n+1) / 2
= (n^2 + n) / 2
Bu değerin Big O değeri 
* O(n^2)

```

3. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

```
18 sayısı 2. indexte yer almaktadır.

```
4. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]

```
---
## **Proje 2**

[16,21,11,8,12,22] -> **Merge Sort**

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```                  
                  |16|21|11|8|12|22|

    |16|21|11|                       |8|12|22|

    |16|21|  |11|                    |8|12|  |22|

    |11|16|21|                       |8|12|22|

                  |8|11|12|16|21|22|

```
2. Big-O gösterimini yazınız.

```
* O(nlogn)

```
---

## **Proje 3**

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> **Binary-Search-Tree** 

Dizinin Binary-Search-Tree aşamalarını yazınız.

```
                |7|5|1|8|3|6|0|9|4|2|
                        * Root 7
                            7
                           / \ 
                          5   8 
                         / \   \ 
                        1   6   9
                       / \
                      0   3
                         / \
                        2   4
                        
    
     

                        



```     



