#Some things to consider 

## 4 MB ~ array of size 10^6 . Or 2-d array of size 10^3*10^3
###Standard Memory limits are of Order of 256MB. You cannot allocate  more than 4 MB space inside a function (it gives segmentation fault). Thus if you have to make an array of size >= 10^6 , make it global or use dynamic memory allocation.


