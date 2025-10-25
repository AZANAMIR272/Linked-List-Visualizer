

# 🔗 Linked List Visualizer – DSA Project

An interactive **Linked List Visualizer** built using **Java + JavaFX**, designed to help students understand how linked lists work step-by-step.
It visually represents every operation such as **insertion, deletion, searching, and reversing**, making complex data structures easy to grasp.
<img width="1364" height="723" alt="Screenshot 2025-10-26 043706" src="https://github.com/user-attachments/assets/b498ecb0-5a9a-4bfd-88e2-483856598463" />

---

## 📖 Overview

This project is part of a **Data Structures & Algorithms (DSA)** course project.
It allows users to **create and manipulate linked lists dynamically** and visualize how nodes connect and move in real time.

The tool is perfect for:

* Students learning DSA concepts
* Teachers explaining linked lists visually
* Beginners struggling with pointer logic

---

## 🚀 Features

### 🔹 Core Functionalities

* Create **Singly** and **Doubly Linked Lists**
* Insert node at **beginning, end, or specific position**
* Delete node by **position or value**
* **Search** for a value with visual highlighting
* **Reverse** the entire list with animated pointer flipping
* **Clear** the list to restart
* Code simulation showing pseudo-code alongside visualization

### 🔹 Visual Enhancements

* Animated node creation and pointer transitions
* Real-time pseudo-code highlighting
* Speed control slider (slow, medium, fast)
* Zoom-in, zoom-out, and reset view options
* Color-coded animations:

  * 🟢 Insertion
  * 🔵 Traversal
  * 🔴 Deletion

---

## 🧠 Learning Objectives

This project demonstrates:

* How linked lists store data using **nodes and pointers**
* Stepwise logic for **traversal, insertion, deletion, and reversal**
* Difference between **singly and doubly** linked lists
* Basic algorithmic time complexity (O(n) operations)




## ⚙️ Installation & Setup

### 1️⃣ Prerequisites

* Install **JDK 17+**
* Install **Maven**
* Ensure **JavaFX SDK** is configured (or use Maven dependencies)

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/LinkedList-Visualizer.git
cd LinkedList-Visualizer
```

### 3️⃣ Run Project

```bash
mvn clean javafx:run
```

or build the JAR:

```bash
mvn clean package
java -jar target/LinkedList-Visualizer-1.0.jar
```

---

## 🧩 How It Works

| Operation                  | Description                                    |
| -------------------------- | ---------------------------------------------- |
| **Insert (Head/Tail/Pos)** | Animates node creation & pointer update        |
| **Delete (Head/Tail/Pos)** | Highlights node → removes it visually          |
| **Search**                 | Traverses nodes until match found              |
| **Reverse**                | Flips pointers and animates node rearrangement |
| **Clear**                  | Removes all nodes gracefully                   |

---

## 🖥️ Dashboard Layout

| Section                    | Description                       |
| -------------------------- | --------------------------------- |
| 🎨 **Visualization Panel** | Displays animated linked list     |
| ⚙️ **Control Bar**         | Buttons for operations            |
| 🧮 **Code Panel**          | Shows pseudo-code while executing |
| 📈 **Speed Slider**        | Controls animation pace           |

---

## 🌟 Example Use Case

1. Create list: `10, 20, 30`
2. Insert `5` at head → new list: `5 → 10 → 20 → 30`
3. Delete `20` → new list: `5 → 10 → 30`
4. Reverse → `30 → 10 → 5`

---

## 🎓 Educational Value

This tool helps visualize **pointer manipulation**, which is often hard to grasp in text-only explanations.
Students can pause, replay, and control animations — making DSA **fun, interactive, and intuitive**.

---




## 🤝 Contributing

Want to improve this project?

1. Fork the repository
2. Create your branch: `feature/new-operation`
3. Commit: `git commit -m "Added circular linked list visualization"`
4. Push and open a Pull Request

---

## 🧾 License

Licensed under the **MIT License**.
You are free to use, modify, and share with proper credit.



## 📬 Contact

**Author:** Azan Amir


