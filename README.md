# Sorting

### Sorting

**Objective:**  
To implement fundamental sorting algorithms: Bubble Sort, Selection Sort, and Insertion Sort.

**Overview:**  
Sorting is a vital operation in computer science, enabling the organization of data in a specific order. Effective sorting is crucial for enhancing search operations and data analysis. Each of the three algorithms has distinct characteristics, advantages, and disadvantages:

- **Bubble Sort:** This simple algorithm repeatedly traverses the list, comparing adjacent elements and swapping them if they are out of order. It’s akin to going through a row of books, swapping any that are incorrectly arranged until everything is in order.

- **Selection Sort:** This algorithm splits the list into sorted and unsorted sections. It continuously selects the smallest (or largest) element from the unsorted section and moves it to the end of the sorted section. Picture picking the smallest item from a pile and setting it aside, repeating this until the pile is gone.

- **Insertion Sort:** This algorithm constructs a sorted array one element at a time, inserting each new element into its correct position within the already sorted portion. Think of sorting playing cards: you take one card from the deck and place it into the right position among the cards that are already arranged.

**Algorithm: Bubble Sort**

1. Start at the beginning of the array.
2. Compare the first two elements.
3. If the first element is greater than the second, swap them.
4. Move to the next pair of adjacent elements and repeat the process.
5. Continue until you reach the end of the array.
6. Repeat the entire process until no swaps are needed.
