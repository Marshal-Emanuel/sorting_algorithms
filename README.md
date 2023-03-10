## 0x1B. C - Sorting algorithms & Big O

### Objectives
* Master at least four different sorting algorithms
* What is the Big O notation, and how to evaluate the time complexity of an algorithm
* How to select the best sorting algorithm for a given input
* What is a stable sorting algorithm

### Reference Materials
* [Sorting Algorithm](https://alx-intranet.hbtn.io/rltoken/-j5MKLBlzZAC2RfJ5DTBIg)
* [Big O Notation](https://alx-intranet.hbtn.io/rltoken/WRvrE2BaNVQFssHiUATTrw)
* [Sorting Algorithm Animations](https://alx-intranet.hbtn.io/rltoken/ol0P7NbYVb5R31iOv4Q40A)
* [15 Sorting Algorithms in 6 minutes](https://alx-intranet.hbtn.io/rltoken/_I0aEvhfJ66Xyob6dd9Utw)
* a [quick tip](https://alx-intranet.hbtn.io/rltoken/YR-VWQbICB59wZs1eAaI3w) to help you test your sorting algorithms with big sets of random integers

### File Description
0. sort.h ----------- header file with all function prototypes
1. print_array.c ---- holds print_array function
2. print_list.c ----- holds print_list function
3. #-O -------------- best case, average case, and worst case time complexities
* print_array.c and print_list.c \(containing the print_array and print_list functions\) will be compiled with my functions.

#### Tasks
* [0.Bubble Sort](https://www.youtube.com/watch?v=lyZQPjUT5B4)
  * File name a). 0-bubble_sort.c -> a function that sorts an array of integers in ascending order using the [Bubble sort algorithm](https://en.wikipedia.org/wiki/Bubble_sort), b). 0-O -> the big O notations of the time complexity of the Bubble sort algorithm with order of best case, average case, worst case.
* [1.Insertion sort](https://www.youtube.com/watch?v=nKzEJWbkPbQ&feature=emb_rel_pause)
  * Files a). 1-insertion_sort_list.c -> a function that sorts a doubly linked list of integers in ascending order using the [Insertion sort algorithm](https://en.wikipedia.org/wiki/Insertion_sort), b). 1-O -> the big O notations of the time complexity of the Insertion sort algorithm, with order of best case, average case, worst case.
* [2.Selection sort](https://www.youtube.com/watch?v=Ns4TPTC8whw)
  * Files a). 2-selection_sort.c -> a function that sorts an array of integers in ascending order using the [Selection sort algorithm](https://en.wikipedia.org/wiki/Selection_sort), b). 2-O -> the big O notations of the time complexity of the Selection sort algorithm with order of best case, average case, worst case.
* [3. Quick sort](https://www.youtube.com/watch?v=ywWBy6J5gz8)
  * Files a). 3-quick_sort.c -> a function that sorts an array of integers in ascending order using the [Quick sort algorithm](https://en.wikipedia.org/wiki/Quicksort), 3-O -> the big O notations of the time complexity of the Quick sort algorithm.
* [4. Shell sort - Knuth Sequence](https://www.youtube.com/watch?v=ddeLSDsYVp8)
  * File 100-shell_sort.c -> a function that sorts an array of integers in ascending order using the [Shell sort algorithm](https://en.wikipedia.org/wiki/Shellsort), using the Knuth sequence;
  * sequence of intervals (a.k.a the Knuth sequence):
    * n+1 = n * 3 + 1
    * 1, 4, 13, 40, 121, ...
   * No big O notations of the time complexity of the Shell sort (Knuth sequence) algorithm needed - as the complexity is dependent on the size of array and gap.
* [5. Cocktail shaker sort](https://www.youtube.com/watch?v=Xmx_6YRBaq8&t=198s)
  * Files a). 101-cocktail_sort_list.c -> a function that sorts a doubly linked list of integers in ascending order using the [Cocktail shaker sort algorithm](https://en.wikipedia.org/wiki/Cocktail_shaker_sort), b). 101-O -> the big O notations of the time complexity of the Cocktail shaker sort algorithm with order of best case, average case, worst case.
* [6. Counting sort](https://www.youtube.com/watch?v=1mh2vilbZMg)
  * Files a). 102-counting_sort.c -> a function that sorts an array of integers in ascending order using the [Counting sort algorithm](https://en.wikipedia.org/wiki/Counting_sort), b). 102-O -> the big O notations of the time complexity of the Counting sort algorithm.

#### Author
[Marshal-Emanuel](https://github.com/Marshal-Emanuel?tab=repositories)
