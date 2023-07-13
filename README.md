[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.


Çözüm-1: 

        [22*,27,16,2,18,6] = n
        [22,27*,16,2,18,6] = n-1
        [16,22,27*,2,18,6] = n-2
        [2,16,22,27*,18,6] = n-3
        [2,16,18,22,27*,6] = n-4
        [2,6,16,18,22,27*] = 1

Çözüm-2:

        Big-O gösterimini yapınız.
        n+(n+1)+(n+2)+(n+3)+(n+4)+1
        = n(n+1)/2
        = (n^2+n)/2
        
        => Big-O = n^2

Çözüm-3:

        Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

        Sıralanmış Hali => [2,6,16,18,22,27]

        Aradığımız sayı = 18
        18 => Dizinin ortasında => "Average Case"


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Çözüm:

        0. Adım => [7,3,5,8,2,9,4,15,6] = n
        1. Adım => [3,7,5,8,2,9,4,15,6] = n-1
        2. Adım => [3,5,7,8,2,9,4,15,6] = n-2
        3. Adım => [2,3,5,7,8,9,4,15,6] = n-3
        4. Adım => [2,3,4,5,7,8,9,15,6] = n-4
