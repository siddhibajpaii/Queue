Aim: Queue implemntation using an array in C++

#Program a: This C++ program implements a basic queue data structure using a fixed-size array. A queue operates on the FIFO (First-In-First-Out) principle, where elements are inserted at the rear and removed from the front. The program provides functions to enqueue (insert) elements, dequeue (remove) elements, peek at the front element, and display the current contents of the queue. It handles edge cases such as checking if the queue is full before insertion and empty before deletion. The queue is managed with two indices, front and rear, to track the first and last elements in the queue. Although this linear queue implementation does not recycle space after dequeuing, it effectively demonstrates the fundamental operations of a queue.

Algorithm:

- Step-1: Start
- Step-2: Initialize: Set front = -1 and rear = -1 to indicate the queue is empty.
- Step-3: Enqueue (Insert element x):
- Step-4: Check if the queue is full (rear == SIZE - 1):
- Step-5: If full, display "Queue is full" and stop.
- Step-6: If the queue is empty (front == -1), set front = 0.
- Step-7: Increment rear by 1.
- Step-8: Assign items[rear] = x.
- Step-9: Display "Inserted: x".
- Step-10: Dequeue (Remove element):
- Step-11: Check if the queue is empty (front == -1 or front > rear):
- Step-12: If empty, display "Queue is empty" and stop.
- Step-13: Display the element at items[front] as removed.
- Step-14: Increment front by 1.
- Step-15: Peek (View front element):
- Step-16: Check if the queue is empty:
- Step-17: If empty, display "Queue is empty" and stop.
- Step-18: Display the element at items[front].
- Step-19: Display (Show all elements):
- Step-20: Check if the queue is empty:
- Step-21: If empty, display "Queue is empty" and stop.
- Step-22: Loop from front to rear and print each element.
- Step-23: End.
