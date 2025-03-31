### kodluyoruz.proje
PAtika.Dev'deki Veri yapıları ve Algoritmalar dersi içeriğinde bulunan projeler.<br>
#  Proje1: İnsertion sort <br>
[22,27,16,2,18,6] -> İnsertion Sort<br>

Soru 1 : Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.<br>
insertion sort aşamaları :<br>
[6,27,16,27,18,22)<br>
[6,2,16,27,18,22,]<br>
[2,6,16,27,18,22]<br>
[2,6,16,22,18,27]<br>
[2,6,16,18,22,27]<br>

Soru 2 : dizinin BigO gösterimini yazınız.<br>
worse case , BigO = O(n^2)<br>

Soru 3:Time complexity, dizi sıralandıktan sonra 18 case'lerden hangisinin kapsamına girer?<br>
dizi sıralandıktan sonra 18 sayısı ortalarda kalıyor, bu nedenle average case olur.<br>

Soru 4: [7,3,5,8,2,9,4,15,6] dizisinin Selection sort'a göre ilk 4 adımını yazınız.<br>
[2,3,5,8,7,9,4,15,6]<br>
[2,3,5,4,8,7,9,5,15,6]<br>
[2,3,4,6,7,9,5,15,8]<br>
[2,3,4,5,7,9,,6,15,8]<br>
# Proje 2: Merge Sort<br>
[16,21,11,8,12,22] -> Merge Sort<br>
Soru 1: yukarıdaki dizinin Sort türüne göre sıralanmış halini yazınız.<br>
[16,21,11] ______ [8,12,22]<br>
[16] __[21]__[11] ___ [8]__ [12]__ [22]<br>
[11,16,21]___ [8,12,22]<br>
[8,11,12,16,21,22]<br>

Soru 2: dizinin BigO gösterimini yazınız .<br>
Merge Sort her zaman O(nLogn) zaman karmaşıklığına sahiptir<br>

# Proje 3: Binary Search Tree <br>
Soru 1: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.<br>
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb. <br>
 Root 7'dir sağında 8 ve 9 bulunur, solunda 2 bulunur <br>
  2 nin solunda 1 ve sıfır sağında 4 bulunur<br> 
  4 ün solunda 3 , sağında 5 ve 6 bulunur<br>
   5 in sağında ise 6 vardır. <br>
   
        7
       / \
      2    8
    /   \    \ 
   1      4     9
 /       /  \
0      3    5   
              \ 
                6













