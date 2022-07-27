# Insertion-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

-Big-O gösterimini yazınız.

-Time Complexity: 

Average case: Aradığımız sayının ortada olması,

Worst case: Aradığımız sayının sonda olması,

Best case: Aradığımız sayının dizinin en başında olması.

-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

*#Insertion Sort Aşamaları  Array'imiz --> [22,27,16,2,18,6]

(n)-------------[22,27,16,2,18,6]

(n-1)-----------[2|27,16,22,18,6]

(n-2)-----------[2,6|16,22,18,27]

(n-3)-----------[2,6,16,18|22,27]     //16 zaten 3. sırada onu değiştirmeden 18'e geçtik.//

#Big O Notation Gösterimi

Worst Case : O(n^2)=n(n-1)+(n+2)...+1

Average Case: O(n^2)

Best Case: O(n)

Tıme Complexity:

Worst Case: [27,22,18,16,6,2] 

Best Case: [2,6,16,18,22,27]

#18 Sayısının Case Durumu

Dizinin sıralanmış hali [2,6,16,18,22,27] bu şekildedir.

18 sayısı bu dizinin ortasındadır yani average case dir.

#[7,3,5,8,2,9,4,15,6] Dizisinin Insertion Sort'a göre ilk 4 Adımı

(n)---------------[7,3,5,8,2,9,4,15,6]

(n-1)-------------[2|3,5,8,7,9,4,15,6]

(n-2)-------------[2,3,4|8,7,9,5,15,6]

(n-3)-------------[2,3,4,5|7,9,8,15,6]

(n-4)-------------[2,3,4,5,6|9,8,15,7]

https://app.patika.dev/
