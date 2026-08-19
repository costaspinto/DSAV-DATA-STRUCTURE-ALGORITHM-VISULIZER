# DSA Visualizer

An interactive web application built with **React** for visualizing fundamental data structures and algorithms through animated, step-by-step operations.

The project is designed to make Data Structures and Algorithms easier to understand by combining interactive visualizations, pseudocode, complexity analysis, and a responsive user interface.

---

## Table of Contents

- [1. Project Overview](#1-project-overview)
- [2. Key Features](#2-key-features)
- [3. Data Structures](#3-data-structures)
- [4. Algorithms](#4-algorithms)
- [5. How the Visualizer Works](#5-how-the-visualizer-works)
- [6. Technical Stack](#6-technical-stack)
- [7. Project Structure](#7-project-structure)
- [8. Local Setup](#8-local-setup)
- [9. Learning Objectives](#9-learning-objectives)
- [10. Deployment](#10-deployment)
- [11. Future Enhancements](#11-future-enhancements)
- [12. Author](#12-author)
- [13. License](#13-license)

---

## 1. Project Overview

**DSA Visualizer** is an interactive educational web application that demonstrates how common data structures and algorithms work internally.

Instead of relying only on static diagrams or code, the application visually represents operations as they happen. This helps users understand concepts such as insertion, deletion, traversal, searching, and sorting.

The application focuses on three core learning areas:

1. **Visual understanding** — See each operation happen.
2. **Algorithmic understanding** — Follow the underlying pseudocode.
3. **Performance understanding** — Review time and space complexity.

### Live Application

The project is deployed through GitHub Pages:

https://costaspinto.github.io/DSAV-DATA-STRUCTURE-ALGORITHM-VISULIZER/

---

## 2. Key Features

### Interactive Visualizations

Operations are presented visually so users can follow the state of a data structure or algorithm during execution.

### Step-by-Step Explanations

The application provides supporting information including:

- Pseudocode
- Key points
- Operation explanations
- Complexity analysis

### Responsive Interface

The interface is designed to work across different screen sizes.

### Dark-Themed UI

A modern dark interface provides a focused environment for studying algorithms and data structures.

### Multiple DSA Concepts

The application covers several fundamental data structures along with commonly studied sorting algorithms.

---

## 3. Data Structures

The current visualizer includes:

### Array

Demonstrates fundamental array operations and how elements are organized in indexed storage.

### Stack

Demonstrates the **LIFO (Last In, First Out)** principle.

Typical operations include:

- Push
- Pop
- Stack inspection

### Queue

Demonstrates the **FIFO (First In, First Out)** principle.

Typical operations include:

- Enqueue
- Dequeue
- Queue inspection

### Linked List

Demonstrates nodes connected through links and provides a visual representation of linked-list operations.

### Binary Search Tree

Visualizes hierarchical tree structures and operations involving ordered nodes.

### Graph

Provides graph visualization and supports traversal concepts including:

- Breadth-First Search (BFS)
- Depth-First Search (DFS)

### Hash Table

Demonstrates key-value storage and hashing concepts.

---

## 4. Algorithms

### Bubble Sort

Visualizes repeated comparisons and swaps between adjacent elements.

**Typical time complexity:**

- Best: O(n)
- Average: O(n²)
- Worst: O(n²)

### Selection Sort

Visualizes the process of repeatedly selecting the smallest element from the unsorted portion.

**Typical time complexity:**

- Best: O(n²)
- Average: O(n²)
- Worst: O(n²)

### Insertion Sort

Visualizes how elements are inserted into their appropriate position within the sorted portion.

**Typical time complexity:**

- Best: O(n)
- Average: O(n²)
- Worst: O(n²)

### Merge Sort

Visualizes divide-and-conquer sorting by recursively dividing the array and merging sorted sections.

**Typical time complexity:**

- Best: O(n log n)
- Average: O(n log n)
- Worst: O(n log n)

---

## 5. How the Visualizer Works

The application follows an interactive visualization workflow:

```text
User selects DSA
        │
        ▼
User selects operation
        │
        ▼
Application initializes data
        │
        ▼
Algorithm executes step-by-step
        │
        ▼
UI animates state changes
        │
        ├──────────────► Pseudocode
        │
        ├──────────────► Key Explanation
        │
        └──────────────► Complexity
```

This structure connects the implementation of an algorithm with its visual behavior.

For example, during a sorting operation, the user can observe comparisons and element movements while simultaneously reviewing the algorithm's logic and complexity.

---

## 6. Technical Stack

### Frontend

- **React.js** — Component-based user interface
- **JavaScript** — Application logic
- **Tailwind CSS** — Utility-first styling

### Animation

- **Framer Motion** — UI and visualization animations

### Graph Visualization

- **D3.js** — Graph and data visualization capabilities

### Icons

- **Lucide React** — Interface icons

### Build & Package Management

- Node.js
- npm

---

## 7. Project Structure

The repository follows a React-based structure:

```text
DSAV-DATA-STRUCTURE-ALGORITHM-VISULIZER/
│
├── public/
│   └── Public assets
│
├── src/
│   └── Application source code
│
├── .gitignore
├── package.json
├── package-lock.json
├── tailwind.config.js
└── readme.md
```

### `src/`

Contains the React application source code, visualization logic, UI components, and algorithm implementations.

### `public/`

Contains static assets used by the application.

### `package.json`

Defines project metadata, dependencies, and available npm scripts.

### `tailwind.config.js`

Contains Tailwind CSS configuration.

---

## 8. Local Setup

### Prerequisites

Install:

- Node.js
- npm

The original project documentation specifies **Node.js v14 or later**.

### 1. Clone the Repository

```bash
git clone https://github.com/costaspinto/DSAV-DATA-STRUCTURE-ALGORITHM-VISULIZER.git
```

### 2. Enter the Project Directory

```bash
cd DSAV-DATA-STRUCTURE-ALGORITHM-VISULIZER
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

Use the npm development script configured in `package.json`:

```bash
npm start
```

If the repository configuration uses a Vite development script instead, use:

```bash
npm run dev
```

### 5. Open the Application

Open the local URL displayed by the development server in your browser.

---

## 9. Learning Objectives

This project demonstrates practical understanding of:

- Fundamental data structures
- Algorithm implementation
- Sorting algorithms
- Graph traversal
- Tree structures
- Hashing concepts
- Algorithm complexity
- React component development
- Interactive UI design
- Animation-driven visualization
- Data visualization
- Frontend state management

The visualizer is particularly useful for connecting theoretical DSA concepts with observable program behavior.

---

## 10. Deployment

The repository has been deployed using **GitHub Pages**.

Live deployment:

https://costaspinto.github.io/DSAV-DATA-STRUCTURE-ALGORITHM-VISULIZER/

The repository also shows GitHub Pages deployment activity.

---

## 11. Future Enhancements

Potential improvements include:

### Additional Data Structures

- Heap
- Trie
- AVL Tree
- Red-Black Tree
- Priority Queue

### Additional Algorithms

- Quick Sort
- Heap Sort
- Binary Search
- Dijkstra's Algorithm
- A* Search
- Floyd-Warshall
- Topological Sort

### Learning Features

- Interactive quizzes
- Operation-by-operation controls
- Play / pause / step controls
- Adjustable animation speed
- Complexity comparison tables
- Algorithm pseudocode highlighting
- User-created datasets

### Developer Features

- Automated testing
- TypeScript migration
- Component-level documentation
- CI/CD workflow
- Performance optimization
- Accessibility improvements

---

## 12. Author

**Costas Pinto**

MCA — Artificial Intelligence & Machine Learning

GitHub:

https://github.com/costaspinto

Project:

https://github.com/costaspinto/DSAV-DATA-STRUCTURE-ALGORITHM-VISULIZER

Live Demo:

https://costaspinto.github.io/DSAV-DATA-STRUCTURE-ALGORITHM-VISULIZER/

---

## 13. License

This project is licensed under the **MIT License**, according to the repository documentation.

See the repository's license file for the complete license terms.

---

## Project Summary for Resume / Portfolio

**DSA Visualizer — Interactive Data Structures & Algorithms Platform**

Developed an interactive React-based learning platform that visually demonstrates fundamental data structures and sorting algorithms. Implemented animated operations with pseudocode and complexity analysis, using Tailwind CSS for the responsive interface, Framer Motion for animations, and D3.js for graph visualization. Deployed the application through GitHub Pages.

### Technologies

**React.js | JavaScript | Tailwind CSS | Framer Motion | D3.js | Lucide React | GitHub Pages**
