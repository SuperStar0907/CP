Binary  Search :  

Try this : http://codeforces.com/problemset/problem/431/D </br>
Understand the concept of binary search. Both left_binary_search and right_binary_search. Try to implement it on your own. Look at others implementation.
sample implementation :

int l = 0, r = 10000,  key_val = SOME_VALUE, m;

while (r - l > 1)

{

m = (l+r) >> 1;

int val = some_non_decreasing_function(m);

if(val < key_val) l = m;

else r = m;

}

if  (some_non_decreasing_function(l) == key_val ) return l;

else return r;

// this can be modified in a variety of ways, as required in the problem

Practice Problems:

http://www.spoj.com/problems/AGGRCOW/  </br>
http://codeforces.com/problemset/problem/431/D  </br>
http://www.spoj.com/problems/PIE/ </br>
http://www.spoj.com/problems/TETRA/ </br>
http://www.spoj.com/problems/KOPC12A/ </br>
