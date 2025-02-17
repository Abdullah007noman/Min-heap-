# Min Heap Implementation in Python
This repository contains a Python implementation of a Min Heap data structure. The heap supports the following functionalities:

* Building a min heap from an array (build_min_heap)
* Heapifying the heap to maintain the min heap property (heapify)
* Inserting new elements into the heap (insert)
* Removing and returning the root (minimum) element from the heap (pop)
* Generic support for different data types (e.g., integers, floats, custom objects)
  
The implementation uses bit manipulation for efficient calculation of parent and child indices.

## Implementation Details
Bit Manipulation for Parent and Child Indices
* Parent Index: (i - 1) >> 1 (equivalent to integer division by 2)
* Left Child Index: (i << 1) + 1 (equivalent to multiplying by 2 and adding 1)
* Right Child Index: (i << 1) + 2 (equivalent to multiplying by 2 and adding 2)

## Key Methods
* build_min_heap(array): Builds a min heap from an input array.
* heapify(i): Ensures the subtree rooted at index i satisfies the min heap property.
* insert(key): Inserts a new element into the heap.
* pop(): Removes and returns the root (minimum) element.

## Usage
To use the min heap implementation, follow these steps:

* 1. Clone the repository:
     
     git clone https://github.com/your-username/min-heap.git
cd min-heap
