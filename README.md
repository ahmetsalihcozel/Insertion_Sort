# Insertion Sort
Bu README.md dosyası [Patika.dev-Insertion_Sort/Selection_Sort](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje) alıştırmaları kapsamında hazırlanmıştır.

### Alıştırma Sorusu :

    [22,27,16,2,18,6] -> Insertion Sort

    Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

    Big-O gösterimini yazınız.

    Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

    Average case: Aradığımız sayının ortada olması
    Worst case: Aradığımız sayının sonda olması
    Best case: Aradığımız sayının dizinin en başında olması.
    .

    [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

### Cevap :

Insertion sort, verilen diziyi küçükten büyüğe sıralamak için kullanılan bir sıralama algoritmasıdır. Aşağıda verilen dizi için yapılan adımlar:

    1. [22,27,16,2,18,6] -> Dizi başlangıçta sıralı değil
    2. [2,27,16,22,18,6] -> Dizideki en küçük eleman olan 2, tespit edilir ve en başa yazılır.
    3. [2,6,16,22,18,27] -> 2'den sonraki en küçük eleman tespit edilir ve 2 sayısının sağındaki 27 sayısı ile yer değişimi(Insertion) uygulanır.
    4. [2,6,16,22,18,27] -> 6'dan sonraki en küçük eleman tespit edilir ve 6 sayısının sağındaki 16 sayısı ile yer değişimi(Insertion) uygulanır.
    5. [2,6,16,18,22,27] -> 16'dan sonraki en küçük eleman tespit edilir ve 16 sayısının sağındaki 22 sayısı ile yer değişimi(Insertion) uygulanır.

    Sonuç: [2,6,16,18,22,27] -> Dizi sıralanmıştır.

Insertion sort'un Big-O değeri, O(n^2) 'dir. Çünkü her döngüde, karşılaştırma ve yer değiştirme işlemleri n defa yapılır.
