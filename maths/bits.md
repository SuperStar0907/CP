Power of BITS

Numbers are stored as binary bits in the memory so bits manipulation are alway faster.
Bitwise or operator    : |
Bitwise and operator : &
Bitwise xor operator  : ^
Bitwise left shift         : <<
Bitwise right shift      : >>
Memset and its uses using function : sizeof()
Bitmask and use of Bitmask in Dynamic Programming [[subset DP]]
Some cool Tricks

n = n * 2 :: n = n << 1
n = n /2  :: n = n >> 1
checking if n is power of 2 (1,2,4,8…) ::checking !(n & (n-1))
if x is max power of 2 dividing n, then x = (n & -n)
Total number of bits which are set in n = __builtin_popcount(n)
setting xth bit of n  :: n |= (1<<x)
checking if xth bit of n is set :: checking if  n&(1<<x) is non zero
Problem : You are given N numbers and a numbers S. Check if there exist some subset of the given numbers which sums equal to S .What if you are asked to compute the number of such subsets ?

Practice :
http://www.spoj.com/problems/SPCO/ </br>
http://codeforces.com/problemset/problem/114/B  </br>
http://www.spoj.com/problems/CLEANRBT/  </br>
More will be added later </br>
Read this for further knowledge

http://community.topcoder.com/tc?module=Static&d1=tutorials&d2=bitManipulation
