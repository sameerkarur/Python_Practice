# 🐍 Python for Data Analysis & Data Science — Practice Hub

A **complete, beginner-friendly** repository to learn and practice Python for Data Analysis and Data Science. It covers **NumPy, Pandas, Matplotlib, and Seaborn** with detailed reference guides, 220+ hands-on practice questions, and ready-to-use Jupyter notebooks — all built around a real-world dataset.

> **Whether you're a beginner starting your data science journey or someone brushing up on fundamentals — this repo has everything you need to practice and build confidence.**

---

## 📌 What's Inside

| Library | Reference Guide | Practice Questions | Jupyter Notebook |
|---|---|---|---|
| **NumPy** | [numpy_basics.md](numpy/numpy_basics.md) | [45 Questions](numpy/numpy_practice.md) | [numpy_practice.ipynb](numpy/numpy_practice.ipynb) |
| **Pandas** | [pandas_basics.md](pandas/pandas_basics.md) | [70 Questions](pandas/pandas_practice.md) | [pandas_practice.ipynb](pandas/pandas_practice.ipynb) |
| **Matplotlib** | [matplotlib_basics.md](matplotlib/matplotlib_basics.md) | [45 Questions](matplotlib/matplotlib_practice.md) | [matplotlib_practice.ipynb](matplotlib/matplotlib_practice.ipynb) |
| **Seaborn** | [seaborn_basics.md](seaborn/seaborn_basics.md) | [60 Questions](seaborn/seaborn_practice.md) | [seaborn_practice.ipynb](seaborn/seaborn_practice.ipynb) |

**Total: 220+ practice questions** ranging from Beginner to Advanced.

---

## 📂 Folder Structure

```
Python_Practice/
│
├── README.md
├── AusApparalSales4thQrt2020.csv    ← Practice dataset
│
├── numpy/
│   ├── numpy_basics.md              ← Syntax reference & cheat sheet
│   ├── numpy_practice.md            ← 45 practice questions
│   └── numpy_practice.ipynb         ← Jupyter notebook to solve in
│
├── pandas/
│   ├── pandas_basics.md
│   ├── pandas_practice.md           ← 70 practice questions
│   └── pandas_practice.ipynb
│
├── matplotlib/
│   ├── matplotlib_basics.md
│   ├── matplotlib_practice.md       ← 45 practice questions
│   └── matplotlib_practice.ipynb
│
└── seaborn/
    ├── seaborn_basics.md
    ├── seaborn_practice.md          ← 60 practice questions
    └── seaborn_practice.ipynb
```

---

## 📊 Dataset

All practice questions use the same dataset: **Australian Apparel Sales — Q4 2020**

| Column | Description |
|---|---|
| `Date` | Date of sale (Oct–Dec 2020) |
| `Time` | Time of day (Morning, Afternoon, Evening) |
| `State` | Australian state (WA, NT, SA, TAS, etc.) |
| `Group` | Customer group (Kids, Men, Women, Seniors) |
| `Unit` | Number of units sold |
| `Sales` | Total sales amount ($) |

**~7,500 rows** of real-world-style sales data — perfect for practicing filtering, grouping, aggregation, and visualization.

---

## 🚀 Getting Started (Step-by-Step)

### 1. Prerequisites

Make sure you have **Python 3.8+** installed. You can check by running:

```bash
python --version
```

If you don't have Python, download it from [python.org](https://www.python.org/downloads/).

### 2. Clone the Repository

```bash
git clone https://github.com/sameerkarur/Python_Practice.git
cd Python_Practice
```

### 3. Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

Or install all at once:

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

This will open Jupyter in your browser. Navigate to any library folder and open the `.ipynb` file.

### 5. Start Practicing!

1. **Open a notebook** (e.g., `numpy/numpy_practice.ipynb`)
2. **Run the setup cell** first (loads the dataset)
3. **Read each question** in the markdown cells
4. **Write your solution** in the empty code cell below
5. **Run your code** with `Shift + Enter`
6. **Stuck?** Open the `_basics.md` file in the same folder for syntax help

---

## 📖 How to Use This Repo

### If you're a **complete beginner**:
1. Start with the **`_basics.md`** files — read through the syntax and examples
2. Then open the **Jupyter notebook** and try the questions
3. Follow this order: **NumPy → Pandas → Matplotlib → Seaborn**

### If you're **intermediate**:
1. Jump straight into the **Jupyter notebooks**
2. Skip to the intermediate/advanced sections
3. Use the `_basics.md` files as a quick reference when needed

### If you're **preparing for interviews**:
1. Focus on **Pandas** (most asked in data analyst interviews)
2. Practice the **groupby, pivot table, and advanced analysis** sections
3. Build visualizations with **Matplotlib & Seaborn** for portfolio projects

---

## 📚 What You'll Learn

### NumPy (45 Questions)
- Array creation, indexing, slicing, reshaping
- Mathematical & statistical operations
- Broadcasting, sorting, filtering
- Random number generation & simulation
- Linear algebra basics

### Pandas (70 Questions)
- Loading & exploring data (CSV, Excel)
- Selecting, filtering, and sorting
- GroupBy, aggregation, and pivot tables
- Handling missing data
- Merging, joining, and concatenating DataFrames
- String operations and datetime handling
- Apply, map, and transform

### Matplotlib (45 Questions)
- Line plots, bar charts, scatter plots
- Histograms, pie charts, box plots
- Subplots and multi-panel figures
- Customization (styles, colors, annotations)
- Heatmaps and dashboard-style visualizations

### Seaborn (60 Questions)
- Distribution plots (histplot, kdeplot, displot)
- Categorical plots (bar, box, violin, swarm, strip)
- Relational plots (scatter, line, regression)
- Heatmaps, pair plots, and joint plots
- FacetGrid for multi-panel analysis
- Themes, palettes, and styling
- Complete EDA (Exploratory Data Analysis) projects

---

## 💡 Tips for Effective Practice

- **Don't just read — code it out.** Muscle memory matters.
- **Try before looking at the reference.** Struggle a bit, then check syntax.
- **Experiment!** Modify the questions, try different parameters.
- **Build a mini-project** after each library — analyze the dataset your own way.
- **Commit your solutions** to track your progress.

---

## 🤝 Contributing

Found a bug? Want to add more questions? Feel free to:
1. Fork this repository
2. Create a new branch
3. Submit a pull request

All contributions are welcome!

---

## ⭐ If You Found This Useful

If this repo helped you in your learning journey, please **give it a star** ⭐ on GitHub — it helps others discover it too!

---

## 📬 Connect

Made with 💻 by [Sameer Karur](https://github.com/sameerkarur)

Feel free to connect on [LinkedIn](https://www.linkedin.com/) if you have questions or feedback!

---

**Happy Learning! 🚀**
