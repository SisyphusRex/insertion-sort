# Insertion Sort
Treats the input as two parts, sorted and unsorted.  Repeatedly inserts the next value from the unsorted part.  
Index starts at 1, assumes index 0 is sorted, and compares index 1 to index 1-1.
Each new element is compared to the previous elements in the sorted list and put into position.

## Complexity

### Best Case
all elements are sorted, look at each once  
O(n)  
Ω(n)  
Θ(n)  

### Average Case


### Worst Case
no elements are sorted, each one must be compared to (n-1) elements
O(n^2)  
Ω(n^2)  
Θ(n^2)  
