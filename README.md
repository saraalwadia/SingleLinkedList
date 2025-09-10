# Java Data Structures Projects

This repository contains multiple data structure implementations in **pure Java** from scratch. Each project demonstrates how classic data structures work internally, without using Java Collections Framework.

---

## Queue (FIFO)

**Description:**  
A simple integer queue following the FIFO (First In First Out) principle.

**Features:**  
- `enqueue(int e)` – Add element to the rear.  
- `dequeue()` – Remove element from the front.  
- `isEmpty()` – Check if queue is empty.  
- `isFull()` – Check if queue is full.

**Code Location:** `queue_lect/Queue.java`

**Example:**
```java
Queue q = new Queue(5);
q.enqueue(10);
q.enqueue(20);
System.out.println(q.dequeue()); // 10
