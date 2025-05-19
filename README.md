# DSA-D3
# P7- Two Pointer Technique
in a given array and a target var.,we have to find values (of arr[i]+arr[j]) that add upto the target.
1. using two for loops or by using two pointer approach, arr[left] &arr[right]
 
# P8- Container With Most Water    
Given an array `height[]` representing vertical lines, find two lines that form a container holding the **maximum water**. The area is determined by:  
**min(height[left], height[right]) × (right - left)**  
 Optimized Solution (Two Pointer)  
1. Start two pointers at the **left** and **right** ends.  
2. Calculate the **area** for the current pair.  
3. Move the pointer with the **smaller height** to maximize water capacity.  
4. Track the maximum area and return it.  

# P9- 3 Sum
find unique triplets that add up to give a sum of zero.
  
1. Sort the array to handle duplicates efficiently.  
2. Fix a pointer (i) and use two moving pointers (j & k).  
3. Check the sum arr[i] + arr[j] + arr[k]:  
   - If sum > target, move k-- (reduce value).  
   - If sum < target, move j++ (increase value).  
   - If sum == target, store the triplet & skip duplicates.  
4. Continue until pointers cross.  



