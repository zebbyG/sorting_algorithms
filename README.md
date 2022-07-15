####  C - Sorting algorithms & Big O

### [0. Bubble sort](0-bubble_sort.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Bubble_sort">Bubble sort</a> algorithm

- Prototype: `void bubble_sort(int *array, size_t size);`
- You’re expected to print the `array` after each time you swap two elements (See example below)
Write in the file `0-O`, the big O notations of the time complexity of the Bubble sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [1. Insertion sort](1-insertion_sort_list.c)

Write a function that sorts a doubly linked list of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Insertion_sort">Insertion sort</a> algorithm

- Prototype: `void insertion_sort_list(listint_t **list);`
- You are not allowed to modify the integer `n` of a node. You have to swap the nodes themselves.
- You’re expected to print the `list` after each time you swap two elements (See example below)
Write in the file `1-O`, the big O notations of the time complexity of the Insertion sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [2. Selection sort](2-selection_sort.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Selection_sort">Selection sort</a> algorithm

- Prototype: `void selection_sort(int *array, size_t size);`
- You’re expected to print the `array` after each time you swap two elements (See example below)
Write in the file `2-O`, the big O notations of the time complexity of the Selection sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [3. Quick sort](3-quick_sort.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Quicksort">Quick sort</a> algorithm

- Prototype: `void quick_sort(int *array, size_t size);`
- You must implement the `Lomuto` partition scheme.
- The pivot should always be the last element of the partition being sorted.
- You’re expected to print the `array` after each time you swap two elements (See example below)
Write in the file `3-O`, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [4. Shell sort - Knuth Sequence](100-shell_sort.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Shellsort">Shell sort</a> algorithm, using the `Knuth sequence`

- Prototype: `void shell_sort(int *array, size_t size);`
- You must use the following sequence of intervals (a.k.a the Knuth sequence):
    - `n+1 = n * 3 + 1`
    - `1`, `4`, `13`, `40`, `121`, `...`
- You’re expected to print the `array` each time you decrease the interval (See example below).

### [5. Cocktail shaker sort](101-cocktail_sort_list.c)

Write a function that sorts a doubly linked list of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Cocktail_shaker_sort">Cocktail shaker sort</a> algorithm

- Prototype: `void cocktail_sort_list(listint_t **list);`
- You are not allowed to modify the integer n of a node. You have to swap the nodes themselves.
- You’re expected to print the `list` after each time you swap two elements (See example below)

Write in the file `101-O`, the big O notations of the time complexity of the Cocktail shaker sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [6. Counting sort](102-counting_sort.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Counting_sort">Counting sort</a> algorithm

- Prototype: `void counting_sort(int *array, size_t size);`
- You can assume that `array` will contain only numbers `>= 0`
- You are allowed to use `malloc` and `free` for this task
- You’re expected to print your counting array once it is set up (See example below)
    - This array is of size `k + 1` where `k` is the largest number in `array`

Write in the file `102-O`, the big O notations of the time complexity of the Counting sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [7. Merge sort](103-merge_sort.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Merge_sort">Merge sort</a> algorithm

- Prototype: `void merge_sort(int *array, size_t size);`
- You must implement the `top-down` merge sort algorithm
    - When you divide an array into two sub-arrays, the size of the left array should always be <= the size of the right array. i.e. `{1, 2, 3, 4, 5}` -> `{1, 2}, {3, 4, 5}`
    - Sort the left array before the right array
- You are allowed to use `printf`
- You are allowed to use `malloc` and `free` only once (only one <strong>call</strong>)
- Output: see example

Write in the file `103-O`, the big O notations of the time complexity of the Merge sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [8. Heap sort](104-heap_sort.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Heapsort">Heap sort</a> algorithm

- Prototype: `void heap_sort(int *array, size_t size);`
- You must implement the `sift-down` heap sort algorithm
- You’re expected to print the `array` after each time you swap two elements (See example below)

Write in the file `104-O`, the big O notations of the time complexity of the Heap sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [9. Radix sort](105-radix_sort.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Radix_sort">Radix sort</a> algorithm

- Prototype: `void radix_sort(int *array, size_t size);`
- You must implement the `LSD` radix sort algorithm
- You can assume that `array` will contain only numbers `>= 0`
- You are allowed to use `malloc` and `free` for this task
- You’re expected to print the array each time you increase your `significant digit` (See example below)

### [10. Bitonic sort](106-bitonic_sort.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Bitonic_sorter">Bitonic sort</a> algorithm

- Prototype: `void bitonic_sort(int *array, size_t size);`
- You can assume that `size` will be equal to `2^k`, where `k >= 0` (when `array` is not `NULL` …)
- You are allowed to use `printf`
- You’re expected to print the `array` each time you swap two elements (See example below)
- Output: see example

Write in the file `106-O`, the big O notations of the time complexity of the Bitonic sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [11. Quick Sort - Hoare Partition scheme](107-quick_sort_hoare.c)

Write a function that sorts an array of integers in ascending order using the <a href="https://en.wikipedia.org/wiki/Quicksort">Quick sort</a> algorithm

- Prototype: `void quick_sort_hoare(int *array, size_t size);`
- You must implement the `Hoare` partition scheme.
- The pivot should always be the last element of the partition being sorted.
- You’re expected to print the `array` after each time you swap two elements (See example below)

Write in the file `107-O`, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:

- in the best case
- in the average case
- in the worst case

### [12. Dealer](1000-sort_deck.c)

Write a function that sorts a deck of cards.

- Prototype: `void sort_deck(deck_node_t **deck);`
- You are allowed to use the C standard library function `qsort`
- Please use the following data structures:


- You have to push you `deck.h` header file, containing the previous data structures definition
- Each node of the doubly linked list contains a card that you cannot modify. You have to swap the nodes.
- You can assume there is exactly `52` elements in the doubly linked list.
- You are free to use the sorting algorithm of your choice
- The deck must be ordered:
    - From `Ace` to `King`
    - From Spades to Diamonds


<a href="https://github.com/zebbyG">zebbyG</a>
<a href="https://github.com/debugulize">debugulize</a>
