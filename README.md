# DSA
Data Structures and Algorithms

  ## Array
- [ ] Implement a vector (mutable array with automatic resizing):
    - [ ] Practice coding using arrays and pointers, and pointer math to jump to an index instead of using indexing.
    - [ ] New raw data array with allocated memory
        - can allocate int array under the hood, just not use its features
        - start with 16, or if starting number is greater, use power of 2 - 16, 32, 64, 128
    - [ ] size() - number of items
    - [ ] capacity() - number of items it can hold
    - [ ] isEmpty()
    - [ ] get(index) - returns item at given index, blows up if index out of bounds
    - [ ] add(item)
    - [ ] add(index, item) - inserts item at index, shifts that index's value and trailing elements to the right
    - [ ] addFirst(item) - can use insert above at index 0
    - [ ] removeLast() - remove from end, return value
    - [ ] delete(index) - delete item at index, shifting all trailing elements left
    - [ ] remove(item) - looks for value and removes index holding it (even if in multiple places)
    - [ ] getFirst(item) - looks for value and returns first index with that value, -1 if not found
    - [ ] resize(new_capacity) // private function
        - when you reach capacity, resize to double the size
        - when popping an item, if size is 1/4 of capacity, resize to half

 ### Linked Lists

    - [ ] Implement Singly Linked List:
        - [ ] size() - returns number of data elements in list
        - [ ] isEmpty() - bool returns true if empty
        - [ ] valueAt(index) - returns the value of the nth item (starting at 0 for first)
        - [ ] addFirst(value) - adds an item to the front of the list
        - [ ] removeFirst() - remove front item and return its value
        - [ ] addLast(value) - adds an item at the end
        - [ ] removeLast() - removes end item and returns its value
        - [ ] getFirst() - get value of front item
        - [ ] getLast() - get value of end item
        - [ ] insert(index, value) - insert value at index, so current item at that index is pointed to by new item at index
        - [ ] remove(index) - removes node at given index
        - [ ] getFromLast(n) - returns the value of the node at nth position from the end of the list
        - [ ] reverse() - reverses the list
        - [ ] remove(value) - removes the first item in the list with this value

    - [ ] Implement Doubly Linked List
        - [ ] size() - returns number of data elements in list
        - [ ] isEmpty() - bool returns true if empty
        - [ ] valueAt(index) - returns the value of the nth item (starting at 0 for first)
        - [ ] addFirst(value) - adds an item to the front of the list
        - [ ] removeFirst() - remove front item and return its value
        - [ ] addLast(value) - adds an item at the end
        - [ ] removeLast() - removes end item and returns its value
        - [ ] getFirst() - get value of front item
        - [ ] getLast() - get value of end item
        - [ ] insert(index, value) - insert value at index, so current item at that index is pointed to by new item at index
        - [ ] remove(index) - removes node at given index
        - [ ] getFromLast(n) - returns the value of the node at nth position from the end of the list
        - [ ] reverse() - reverses the list
        - [ ] remove(value) - removes the first item in the list with this value

     ### Stack
      - [ ] Implement with Array
        - [ ] push(value)
        - [ ] pop()
        - [ ] peek()
        - [ ] isEmpty()
        - [ ] isFull()
        - [ ] size()

      - [ ] Implement with Singly Linked List
          - [ ] push(value)
          - [ ] pop()
          - [ ] peek()
          - [ ] isEmpty()
          - [ ] isFull()
          - [ ] size()

     ### Queue

      - [ ] Implement using Array:
          - [ ] enqueue(value) - adds item at end of available storage
          - [ ] dequeue() - returns value and removes least recently added element
          - [ ] isEmpty()
          - [ ] isFull()
          - [ ] size()

      - [ ] Implement using Linked List, with Tail Pointer:
          - [ ] enqueue(value) - adds value at position at tail
          - [ ] dequeue() - returns value and removes least recently added element (front)
          - [ ] isEmpty()
          - [ ] isFull()
          - [ ] size()

   ### Hash table
      - [ ] Implement using array using Linear Probing Stratergy
          - [ ] hash(k, m) - m is size of hash table
          - [ ] put(key, value) - if key already exists, update value
          - [ ] containsKey(key)
          - [ ] get(key)
          - [ ] remove(key)
