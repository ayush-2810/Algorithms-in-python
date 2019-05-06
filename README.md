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
   
  
 - ## **Subarray** : This file contains a way to make all **subarrays** from a given **list**.  
 
   - It also uses **itertools** module.  
   - It uses function **combination** to generate all **subarrays**.  


- ## **Merge_sort** : This file contains the algorithm of sorting which sorts the list in ascending order. Name of the algorithm is merge sort.  

     - **Merge** **Sort** is a **Divide and Conquer** algorithm. It divides input array in two halves, calls itself for the two halves and then merges the two sorted halves.  
     - **Time** **complexity** : 
        - Best case :  O(nlog(n)
        - Average case : O(nlogn)
        - Worst case : O(nlogn)
    - **Space** **complexity** : O(n) 
     
     
- ## **Rabin_karp** : This file contains an algorithm which finds the number of occurences in a given text.  

  - Like the Naive Algorithm, **Rabin-Karp** algorithm also slides the pattern one by one. But unlike the Naive algorithm, Rabin Karp algorithm matches the **hash** **value** of the pattern with the hash value of current substring of text, and if the hash values match then only it starts matching individual characters. So Rabin Karp algorithm needs to calculate hash values for following strings.  
  - Time complexity : 
      - **Best_case** **complexity** : O(n+m)
      - **Average_case** **complexity** : O(n+m)
      - **Worst_case** **complexity** : O(nm)  
      
      
- ## Radix_sort : This file contains an algorithm which sorts the list in ascending order. Name of the algorithm is radix sort.  
     - **Time** **complexity** : O((n+b) * logb(k)) (b is for representing base of the numbers, k is the maximum possible value  and n is number 
     of elements.  
     
     
- ## Bubble_sort : This file contains an algorithm which sorts the list in ascending order. Name of the algorithm is bubble sort.   
     - **Time** **complexity** : 
        - Best case :  O(n)
        - Average case : O(n<sup>2</sup>)
        - Worst case : O(n<sup>2</sup>)
    - **Space** **complexity** : O(1)   
     
     
- ## Insertion_sort : This file contains an algorithm which sorts the list in ascending order. Name of the algorithm is insertion sort.
    - **Time** **complexity** : 
      - Best case :  O(n)
      - Average case : O(n<sup>2</sup>)
      - Worst case : O(n<sup>2</sup>)
    - **Space** **complexity** : O(1) 
    
    
- ## **Integer_extractor** : This file contains a code to extract all the integers from a given string.


- ## Selection_sort : This file contains an algorithm which sorts the list in ascending order. Name of the algorithm is insertion sort.
    - **Time** **complexity** : 
      - Best case :  O(n<sup>2</sup>)
      - Average case : O(n<sup>2</sup>)
      - Worst case : O(n<sup>2</sup>)
    - **Space** **complexity** : O(1)  
    
    
- ## Quick_sort : This file contains an algorithm which sorts the list in ascending order. Name of the algorithm is quick sort.
    - **Time** **complexity** : 
      - Best case : O(nlogn)
      - Average case : O(nlogn)
      - Worst case : O(n<sup>2</sup>)
    - **Space** **complexity** : O(1)  
