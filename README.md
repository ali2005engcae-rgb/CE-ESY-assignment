Circular Buffer in C

 Description
This project implements a **Circular Buffer (Ring Buffer)** in C.  
A circular buffer is a fixed-size data structure that wraps around when it reaches the end.

The program:
1. Takes a user's name as input.
2. Appends `"CE-ESY"` to the name.
3. Stores the result in a circular buffer.
4. Reads and prints the stored characters in order.



 Features
- Initialize buffer
- Check if buffer is full or empty
- Write data to buffer
- Read data from buffer
- Handle overflow and underflow cases


Data Structure

c
typedef struct {
    char buffer[SIZE];
    int head;
    int tail;
    int count;
} CircularBuffer;
