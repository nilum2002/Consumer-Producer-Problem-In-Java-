🧵 Producer-Consumer Problem in Java

📝 Description
The Producer-Consumer Problem is a classic example of a multi-process synchronization challenge in concurrent programming. It involves two types of threads — Producers and Consumers — that share a common bounded buffer (like a queue).

Producers generate data and place it into the buffer.
Consumers take data from the buffer and process it.

The key constraints:
The producer must wait if the buffer is full.
The consumer must wait if the buffer is empty.
Both must operate safely without corrupting the shared data structure (avoiding race conditions).

This problem demonstrates practical usage of thread synchronization in Java using tools like:
wait() and notifyAll() for thread communication.
synchronized blocks for critical section protection.

💡 Java Solution
This solution uses a bounded buffer (a simple queue) and a shared monitor to ensure proper synchronization between producer and consumer threads.

✅ Features
Thread-safe queue access
Proper wait-notify coordination
Works with multiple producers and consumers

🚀 How to Run
Clone the repository:
git clone [https://github.com/your-username/ProducerConsumerJava.git](https://github.com/nilum2002/Consumer-Producer-Problem-In-Java-)

📚 Concepts Covered
Multithreading
Inter-thread communication
Critical section handling

wait-notify mechanism

🔗 References
Oracle Java Docs: Concurrency

GeeksforGeeks: Producer Consumer Problem
