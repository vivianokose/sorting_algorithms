# 0x1B. C - Sorting algorithms & Big O

This repository contains the source code and documentation for the "Sorting algorithms & Big O" project, which is part of the Holberton School curriculum. The project focuses on understanding and implementing various sorting algorithms in the C programming language and analyzing their time complexity using Big O notation.

## Project Overview

The "Sorting algorithms & Big O" project aims to develop a deep understanding of sorting algorithms and their efficiency. It involves implementing several sorting algorithms such as bubble sort, insertion sort, selection sort, quicksort, and merge sort in the C programming language. Additionally, it explores the concept of Big O notation and analyzes the time complexity of these sorting algorithms.

## Project Structure

The project is structured as follows:

- **sorts/**: This directory contains the implementation of different sorting algorithms in separate C files, each with its own header file. For example, bubble sort is implemented in `0-bubble_sort.c` and `sort.h`.
- **main/**: This directory contains files for testing and showcasing the sorting algorithms. Each algorithm is tested with various scenarios to demonstrate its functionality.
- **big_o/**: This directory contains analysis files that explain the time complexity of the sorting algorithms using Big O notation.
- **README.md**: This file provides an overview and instructions on how to use the project.

## Sorting Algorithms

The following sorting algorithms are implemented in this project:

1. Bubble Sort: This algorithm repeatedly swaps adjacent elements if they are in the wrong order.
2. Insertion Sort: This algorithm builds the final sorted array one item at a time by inserting each element into its correct position.
3. Selection Sort: This algorithm sorts an array by repeatedly finding the minimum element and swapping it with the current element.
4. Quick Sort: This algorithm uses a divide-and-conquer strategy to recursively partition the array and sort it.
5. Merge Sort: This algorithm divides the array into two halves, recursively sorts them, and then merges the sorted halves.

## Usage

To use the sorting algorithms, follow these steps:

1. Clone the repository: `git clone https://github.com/your_username/sorting-algorithms-big-o.git`
2. Navigate to the project directory: `cd sorting-algorithms-big-o`
3. Use the `gcc` command to compile the sorting algorithm of your choice. For example, to compile bubble sort, run: `gcc -Wall -Werror -Wextra -pedantic -o bubble 0-bubble_sort.c main/0-main.c`.
4. Run the compiled executable to see the sorted array. For example: `./bubble`.

## Time Complexity Analysis

The time complexity of each sorting algorithm is analyzed using Big O notation and documented in the `big_o` directory. The time complexity represents the upper bound of the running time as the input size approaches infinity.

## Contributing

Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please create a pull request or submit an issue on the GitHub repository.
