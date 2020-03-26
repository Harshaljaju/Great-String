# Great-String
"""
In JKLU, Mid term-1 examination is going on. Samyak, a student of second year, comes late in examination hall.
Now he can only solve first problem of question paper in remaining time. He was stuck in solving problem as
he was weak in strings. For solving problem in time, he has asked your help for solving it.
In his problem he has to check weather string S is great or not. A string is called great if it can be
represented as exactly R concatenated copies of some string. You are given a string S, consisting of l
owercase English letters and a positive integer R. your task is to reorder the letters in the string S
in such a way that the resulting string is a lexicographically smallest great string. If the great string
not exist print -1. Lexicographically smallest string means letters of string are in alphabetically order
  .E.g. In string baa, aab, aba order of lexicographically smallest string is aab,aba,baa.

Input Format

The first line contains positive integer T represents the no of test cases in the input file.
Each test case contains 2 lines. First line contains positive integer R and second line contains string S.
All characters in S are lowercase English letters.

Constraints

1≤ T ≤ 100

1 ≤ R ≤ 1000

1 ≤ string length ≤ 1000

Output Format

For each test case print the lexicographically smallest great string on a single line. If the string is not great, print -1.

Sample Input 0

2
4
baaaabbbaaaa
5
baaaabbbaaaa
Sample Output 0

aabaabaabaab
-1
Explanation 0

Explanation of test case 1: String S is ordered as aabaabaabaab, as aab is repeating 4 times in string S,
so string S is great string.
TIME LIMIT: 1 second
"""
