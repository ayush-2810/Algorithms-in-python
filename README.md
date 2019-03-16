# Algorithms-in-python
This repository contains **algorithms** in **python**.

- ## **Euclidean_gcd** : This file **contains** the  **Euclidean** **Algorithm** to compute **gcd** of two numbers.  

  ### Basic Euclidean Algorithm for GCD :
  The algorithm is based on below facts.

     - If we subtract smaller number from larger (we reduce larger number), GCD doesn’t change. So if we keep subtracting repeatedly the larger of two, we end up with GCD.  
     - Now instead of subtraction, if we divide smaller number, the algorithm stops when we find remainder 0.


- ## **Unordered_pairs** : This file contains an in-built function which can be used for making all unordered pairs from a given list.    

   - It uses **itertools** module.
   - It contains a function named **combination** which is used to generate all the **pairs** from a list.  
   
  
 - ## Subarray : This file contains a way to make all **subarrays** from a given **list**.  
 
   - It also uses **itertools** module.  
   - It uses function **combination** to generate all **subarrays**.  


- ## **Merge_sort** : This file contains the algorithm of sorting which sorts the list in ascending order. Name of the algorithm is merge sort.  

     - **Merge** **Sort** is a **Divide and Conquer** algorithm. It divides input array in two halves, calls itself for the two halves and then merges the two sorted halves.  
     - **Time** **complexity** : O(nlog(n)).  
     - Space complexity : O(n).  
     
