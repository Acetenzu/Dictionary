# Dictionary
This project can help you to read the file and to know how many words in the file.

瑪奇瑪給了你一份惡魔辭典（dictionary.txt），裡面有許多單字。請設計一個程式，完成以下任務：

1. 讀取檔案 dictionary.txt，把所有單字存成一個 list。
2. 設計三個函式：
 Count_Words() : 回傳字典中共有多少個單字(含字母)。
 Find_Longest() : 回傳一個(或多個) tuple，格式為 (word, length)，代表最長的單字與它的長度。
 Find_Shortest() : 回傳一個(或多個) tuple，格式為 (word, length)，代表最短的單字與它的長度。
3. 主程式輸出：
輸出單字總數
輸出最長單字（可能不只一個）
輸出最短單字（可能不只一個）

Input

不需要使用者輸入，程式直接讀取 dictionary.txt

Output

程式需要依序輸出：

總共有 <單字數> 個單字

最長的單字有:

[(word1, 長度), (word2, 長度), ...]

最短的單字有:

[(word1, 長度), (word2, 長度), ...]

*有無空格、大小寫、符號、換行請同學再多比對一下，建議直接複製範例測資的文字*

*一定要用函式*

Sample Input

(dictionary.txt) 

Sample Output 1

A,a,aa,aal,aalii,aam,Aani,aardvark,aardwolf,Aaron,Aaronic,Aaronical,Aaronite,…

總共有 234936 個單字

最長的單字有:

[('formaldehydesulphoxylate', 24),

('pathologicopsychological', 24),

('scientificophilosophical', 24),

('tetraiodophenolphthalein', 24),

('thyroparathyroidectomize', 24)]
最短的單字有:
[('A', 1), ('a', 1), ('B', 1), ('b', 1), ('C', 1),
('c', 1), ('D', 1), ('d', 1), ('E', 1), ('e', 1), ('F',
1), ('f', 1), ('G', 1), ('g', 1), ('H', 1), ('h', 1),
('I', 1), ('i', 1), ('J', 1), ('j', 1), ('K', 1), ('k',
1), ('L', 1), ('l', 1), ('M', 1), ('m', 1), ('N', 1),
('n', 1), ('O', 1), ('o', 1), ('P', 1), ('p', 1), ('Q',
1), ('q', 1), ('R', 1), ('r', 1), ('S', 1), ('s', 1),
('T', 1), ('t', 1), ('U', 1), ('u', 1), ('V', 1), ('v',
1), ('W', 1), ('w', 1), ('X', 1), ('x', 1), ('Y',
1), ('y', 1), ('Z', 1), ('z', 1)]
