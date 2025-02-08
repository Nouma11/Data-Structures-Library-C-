# Data Structures Library (C++) 🚀

A powerful collection of **Data Structures** implemented in **C++**, designed for educational and practical use. This project provides **custom implementations** of **dynamic arrays, linked lists, stacks, queues, and more**, with additional utility functions.

## 📌 Features
✅ **Custom Linked List & Dynamic Array Implementations**  
✅ **Queue & Stack using both Linked List and Dynamic Arrays**  
✅ **Undo/Redo String Manipulation with Stacks**  
✅ **Efficient Memory Management & Clear API**  
✅ **Fully Encapsulated & Extendable Design**  

## 📂 Project Structure

## 📜 Implemented Classes
| Class | Description |
|--------|------------|
| `clsDynamicArray<T>` | A **dynamic array** with insert, delete, resize, and reverse functions. |
| `clsDblLinkedList<T>` | A **doubly linked list** supporting insertion, deletion, and traversal. |
| `clsQueue<T>` | A **queue** implemented using a **doubly linked list**. |
| `clsQueueArr<T>` | A **queue** implemented using a **dynamic array**. |
| `clsStack<T>` | A **stack** built on a **doubly linked list**. |
| `clsStackArr<T>` | A **stack** implemented using a **dynamic array**. |
| `clsMyString` | A **string wrapper** with **undo/redo** functionality using stacks. |

## 🛠 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/DS_Head.git
cd DS_Head
g++ -o main src/main.cpp
./main

clsStackArr<int> myStack;
myStack.Push(100);
myStack.Push(200);
cout << "Top: " << myStack.Top() << endl;
myStack.Pop();

clsMyString myStr;
myStr.Value = "Hello";
myStr.Value = "World";
myStr.Undo();
cout << myStr.Value;  // Output: Hello


---

### 📌 What This Updated README Provides:
✔ **Includes `clsQueueArr` and `clsStackArr`**  
✔ **Documents all classes in your DS project**  
✔ **Professional & Structured Documentation**  
✔ **Easy Setup & Usage Instructions**  
✔ **Encourages Open Source Contributions**  

Now, your **GitHub project will look even more complete and polished**! 🚀🔥
