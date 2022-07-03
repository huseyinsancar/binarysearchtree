# Proje 3
## [www.patika.dev](www.patika.dev)

_____________________________________________


```
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 
```
* Dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


* İlk değer olan 7 root seçilir. </br> 
* 5 değeri root değerinden küçük olduğu için sol tarafa yazılır.</br> 
* 1 değeri 7 değerinden küçük olduğu için sol tarafa gidilir. 5 değerinden de küçük olduğu için 5 in soluna yazılır.</br> 
* 8 değeri 7 değerinden büyük olduğu için sağ tarafa yazılır.</br> 
* 3 değeri 7 den ve 5 den küçük 1 den büyük olduğu için 1 in sağ tarafa yazılır.</br> 

* 6 değeri 7 den küçük 5 den büyük olduğu için 5 ün sağına yazılır.</br> 
* 0 değeri 7 den, 5 den ve 1 den küçük olduğu için 1 in soluna yazılır. </br> 
* 9 değeri 7 den ve 8 den büyük olduğu için 8 in sağına yazılır. </br> 
* 4 değeri 7 den,5 den küçük 1 den ve 3 den büyük olduğu için 3 ün sağına yazılır.</br> 
* 2 değeri 7 den ve 5 den küçük, 1 den büyük, 3 den küçük olduğu için 3 ün soluna yazılır.</br> 

```
          7
        /    \ 
       5      8  
      / \      \
     1   6      9
    / \
   0   3   
      / \
     2   4    
```



