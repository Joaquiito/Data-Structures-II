# Data Structures II

## 📌 Overview
This project is part of the **Data Structures and Algorithms** course.  
It implements a **Salesperson Management System** using multiple data structures to efficiently store, search, and manage data:

1. **Separate Chaining Hash Table** (*Rebalse Separado*).
2. **Binary Search Tree (BST)** (*Árbol Binario de Búsqueda – ABB*).
3. **Sales List** (*Lista de Ventas – LV*).
4. **Quadratic Probing Hash Table** (*Rebalse Abierto Cuadrático – RAC*).

Each structure serves a specific purpose in managing salespeople and their transactions, demonstrating the trade-offs between hashing, trees, and list-based storage.

## 🧠 Implemented Data Structures
### 1. Separate Chaining (Rebalse Separado)
- Hash table where collisions are handled using **linked lists**.
- Efficient insertion and deletion for uniformly distributed keys.

### 2. Binary Search Tree (ABB)
- Stores salespeople in sorted order.
- Allows fast in-order traversal, insertion, and search.

### 3. Sales List (LV)
- Linked list storing sales transactions.
- Associated with salespeople to track their activity.

### 4. Quadratic Probing (RAC – Rebalse Abierto Cuadrático)
- Open addressing hash table with **quadratic probing** collision resolution.
- Avoids clustering issues present in linear probing.

## 🛠 Technologies Used
- **C Language**
- **Standard C Libraries** (`stdio.h`, `stdlib.h`, `string.h`, `ctype.h`)
