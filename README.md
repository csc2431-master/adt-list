# Implementation of Abstract Data Type List: Double Linked List

## Purpose
The goal of this lab is to implement class DLinkedList.

## Design
Class `DLinkedList` is a subclass of `List`, and it implements all virtual
pure methods from class `List`. Remember that this class uses nodes that have a pointer
to the next and previous links on the list:
```
struct Node{
  Object* data;
  Node* next;
  Node* prev;
 };
```
Additionally, this class has a pointer to the last element of the list: `_tail`.

## What is given?
- `dlinkedlist.h` the declaration of the class
- `dlinkedlist.cpp` the method stubs ready for you to fill in the implementation of each method
- `test.cpp` the modified Unit Test, this unit test will test all implementations, you are responsible of passing all 55 tests for variable array lists and all 55 tests for double linked lists. It is possible that you passed the tests from variable array list before and not now, make sure to pass them now.
- Other classes, all classes discussed during the ADT List unit.


## What is expected?
- Your code ***must*** compile.
- Your grade will be *almost* the percentage of your passed unit tests.
- Your code needs to show good programming practices: indentation, meaningful 
variable names, identifiers convention (CamelCase for functions, camelCase 
for variables, _camelCase for data members, SNAKE_CASE for constants), 
header comments, correct file names, etc. Failure to code appropriate will 
result in strong points penalization.
