# [16,21,11,8,12,22] -> Merge Sort
### 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Adım 1: [16, 21, 11, 8, 12, 22]  
Diziyi ikiye böleriz: [16, 21, 11] ve [8, 12, 22]  
Adım 2: [16, 21, 11]  

Bu alt dizi için yine ikiye bölme işlemi yapılır: [16] ve [21, 11]  
Adım 3: [21, 11]

Bu alt dizi için yeniden ikiye bölme işlemi yapılır: [21] ve [11]  
Adım 4: [21] ve [11]

İki alt diziyi birleştiririz ve sıralarız: [11, 21]  
Adım 5: [16] ve [11, 21]

İki alt diziyi birleştiririz ve sıralarız: [11, 16, 21]  
Adım 6: [8, 12, 22]

Bu alt dizi için yine ikiye bölme işlemi yapılır: [8] ve [12, 22]  
Adım 7: [12, 22]

Bu alt dizi için yeniden ikiye bölme işlemi yapılır: [12] ve [22]  
Adım 8: [12] ve [22]

İki alt diziyi birleştiririz ve sıralarız: [12, 22]  
Adım 9: [8] ve [12, 22]

İki alt diziyi birleştiririz ve sıralarız: [8, 12, 22]  
Adım 10: [11, 16, 21] ve [8, 12, 22]

İki alt diziyi birleştiririz ve sıralarız: [8, 11, 12, 16, 21, 22]  
Sonuç olarak, verilen dizi Merge Sort kullanılarak sıralandığında [8, 11, 12, 16, 21, 22] şeklinde sıralanmış dizi elde edilir.
### 2) Big-O gösterimini yazınız.
Merge Sort'un Big O gösterimi O(n log n)'dir. Bu, verilen dizinin uzunluğunun n olduğunu varsayarsak, Merge Sort'un ortalama ve en kötü durumlarda n log n adımda çalışacağı anlamına gelir. Merge Sort, diziyi sürekli olarak ikiye böldüğü için her seviyede n adım gerekmektedir ve toplamda log n seviyesi vardır. Dolayısıyla, n log n adım sayısıyla Merge Sort, genellikle etkili bir sıralama algoritması olarak kabul edilir.
