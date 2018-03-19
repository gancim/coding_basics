# Memory

## Stack vs Heap

Both are stored in computer's RAM:

### Stack: static memory allocation

1) Variables allocated directly in memory and fast access
2) LIFO order most recently used block will be the first to be freed
3) You can use it if you know exactly how much data you need and its not too big
4) Thread specific

### Heap: dynamic memory allocation

1) Variable allocated at run time and bit lower access
2) Element can be accessed randomly at any time
3) You can use it if you don't know how much data you need and its a lot of data
4) Application specific
