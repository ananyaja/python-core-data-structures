# Python Core Data Structures & Collections

A comprehensive collection of Jupyter Notebooks (`.ipynb`) covering fundamental and advanced built-in data structures in Python. Designed as a hands-on reference for core concepts, time complexities, built-in methods, and practical use cases.

---

## 📁 Repository Contents

1. **`Lists_and_Tuples.ipynb`**
   - **Python Lists:** Ordered, mutable sequences. Covers list creation, indexing, slicing, methods (`append`, `extend`, `insert`, `remove`, `pop`), sorting, and nested lists.
   - **Python Tuples:** Ordered, immutable sequences. Covers tuple packing/unpacking, immutability workarounds, memory efficiency, and hashability.
   - **Puzzles & Examples:** Includes the classic *Mutable Default Argument Trap* and matrix addition examples.

2. **`Sets_and_Dictionaries.ipynb`**
   - **Python Sets:** Unordered collections of unique elements. Covers membership testing, mathematical operations (union, intersection, difference), and deduplication patterns.
   - **Python Dictionaries:** Key-value mappings with $O(1)$ lookup time. Covers constructors, methods (`get`, `keys`, `values`, `items`, `update`), and real-world patterns like word frequency counters using `.get(item, 0)`.

---

## 🚀 Quick Start / Running Locally

You can open these notebooks directly in **Google Colab** or run them locally via Jupyter:

```bash
# Clone the repository
git clone https://github.com/your-username/python-core-data-structures.git

# Navigate into the folder
cd python-core-data-structures

# Launch Jupyter Notebook
jupyter notebook
```

---

## 💡 Key Takeaways & Cheat Sheet

| Data Structure | Ordered? | Mutable? | Allows Duplicates? | Average Lookup Time |
| :--- | :--- | :--- | :--- | :--- |
| **List** (`[]`) | Yes | Yes | Yes | $O(n)$ |
| **Tuple** (`()`) | Yes | No | Yes | $O(n)$ |
| **Set** (`{}`) | No | Yes (add/remove) | No | $O(1)$ |
| **Dictionary** (`{k:v}`) | Yes (3.7+) | Yes | Keys: No, Values: Yes | $O(1)$ |