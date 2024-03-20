# Day1-Leetcode75--Greatest-Common-Divisor-of-Strings
To find the GCD among the strings


Algorithm to appoarch the solution is to follow these steps,
1. find the value is equal or not equal while concatenating them, they should equal else return none
2. if equal find the max_len between the len(str1) and len(str2)
3. find gcd for the max_len
4. return str1 's preffix value which should be equal to the max_len
