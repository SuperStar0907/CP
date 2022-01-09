GREEDY ALGORITHMS

Greedy Algorithms are one of the most intuitive algorithms. Whenever we see a problem we first try to apply some greedy strategy to get the answer(we humans are greedy, aren’t we :P ? ).

Read this tutorial for further insight or you can directly attempt the problems most of the greedy approaches are quite simple and easy to understand/formulate.But many times the proving part might be difficult. But you should always try to prove your greedy approach because most the times it happens that you later realise that you solution does not give the optimal answer.

http://community.topcoder.com/tc?module=Static&d1=tutorials&d2=greedyAlg

They are generally used in optimization problems and there exists an optimal substructure to the problem and solutions are generally O(n log n) (sorting) or O(n) (single pass).

Problems List:

http://www.spoj.com/problems/BAISED/ 
http://www.spoj.com/problems/BALIFE/
http://www.spoj.com/problems/GCJ101BB/
http://www.codechef.com/problems/FGFS
http://www.codechef.com/problems/KNPSK
http://www.codechef.com/problems/LEMUSIC
http://www.spoj.com/problems/ARRANGE/
http://www.spoj.com/problems/FASHION/

Q)A thief breaks into a shop and finds there are N items weight of ith item is Wi and cost of ith item is Ci and thief has a bag of which can carry at most W units of weight. Obviously thief wants to have maximum profit . What strategy he should choose if :

Case 1: If he is allowed to take fractional part of items (like assume item to be a bag of rice and you can take whatever fraction of rice you want). [Hint :: greedy])

Case 2:If he cannot break the items in fractional parts. Will now greedy work ? Try to make some test cases for which greedy will fail.

Most of time when greedy fails its the problem can be solved by Dynamic Programming(DP).
