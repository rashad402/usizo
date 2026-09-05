# CS Foundation Series — Presentation Web Apps & Labs

Clean, modern, distraction-free presentation web apps and companion Google Colab practice workbooks for university lectures and coding workshops.

---

## 📚 Available Lectures

| Lecture | Topic | Presentation Deck | Companion Practice Notebook | Slide Count |
| :--- | :--- | :--- | :--- | :--- |
| **Lecture 1** | Introduction to Programming & Python | [`Lecture_1.html`](file:///d:/Usizo%20Lecture/Lecture_1.html) (or `index.html`) | [`python_foundations_practice.ipynb`](file:///d:/Usizo%20Lecture/python_foundations_practice.ipynb) | 23 Slides |
| **Lecture 2** | NumPy & Numerical Computing | [`Lecture_2.html`](file:///d:/Usizo%20Lecture/Lecture_2.html) | [`numpy_practice.ipynb`](file:///d:/Usizo%20Lecture/numpy_practice.ipynb) | 24 Slides |

> [!TIP]
> Both presentation web apps include an interactive header switcher to seamlessly toggle between Lecture 1 and Lecture 2.

---

## 🚀 How to Run Presentations

### Method 1: Direct File Open (Easiest)
Simply double-click `index.html` (Lecture 1) or `Lecture_2.html` (Lecture 2) in any modern web browser (Chrome, Edge, Brave, Firefox, Safari).

### Method 2: Local HTTP Server (Recommended)
Open a terminal in this folder and run:
```bash
python -m http.server 8000
```
Then navigate to:
- `http://localhost:8000/Lecture_1.html` for **Lecture 1**
- `http://localhost:8000/Lecture_2.html` for **Lecture 2**

---

## 📓 Google Colab Practice Notebooks

Each lecture is paired with a companion workbook built with an **inductive learning design** (*Observe & Predict $\rightarrow$ Experiment $\rightarrow$ Solve $\rightarrow$ Self-Check* with automated `assert` tests):

### 1. Python Foundations Workbook
- **File:** [`python_foundations_practice.ipynb`](file:///d:/Usizo%20Lecture/python_foundations_practice.ipynb) (63 cells across 6 modules)
- **Topics:** `print()` formatting, escape sequences, variables, data types, tokens, all 7 operator families, expressions vs. statements, PEMDAS precedence, and type casting.
- **Capstone:** *"The Usizo Smart Chai Counter POS"* bill calculator and receipt generator.

### 2. NumPy & Numerical Computing Workbook
- **File:** [`numpy_practice.ipynb`](file:///d:/Usizo%20Lecture/numpy_practice.ipynb) (55 cells across 7 modules)
- **Topics:** Memory layout (pointers vs. contiguous C-arrays), array creation routines (`zeros`, `ones`, `full`, `arange`, `linspace`), stochastic generation, indexing & slicing, the crucial View vs. Copy trap, vectorized operators & broadcasting, universal functions (ufuncs), axis-wise aggregations, and linear algebra (`@` matmul, `np.linalg.inv`).
- **Core Challenges:** POS bill calculation, multi-body kinetic energy (E_k = ½mv²), and 2D triangle centroid.
- **Capstone:** *"Usizo Weather & Environmental Station Pipeline"* with outlier imputation and Min-Max normalization.

### How to Open in Google Colab:
1. Open [Google Colab](https://colab.research.google.com/).
2. Click **File** &rarr; **Upload notebook**.
3. Select either `python_foundations_practice.ipynb` or `numpy_practice.ipynb` from this folder.

---

## ⌨️ Presentation Keyboard Shortcuts

| Key | Action |
| :--- | :--- |
| <kbd>→</kbd> / <kbd>Space</kbd> / <kbd>PageDown</kbd> | **Next Slide** |
| <kbd>←</kbd> / <kbd>PageUp</kbd> | **Previous Slide** |
| <kbd>Home</kbd> / <kbd>End</kbd> | **First / Last Slide** |
| <kbd>G</kbd> | **Toggle Slide Grid Overview** (Jump directly to any slide) |
| <kbd>F</kbd> | **Toggle Fullscreen Presentation Mode** |
| <kbd>Esc</kbd> | Close Modals & Overviews |
