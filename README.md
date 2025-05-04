# 📊 Data Analysis and Visualization Using OS Concepts  
**Faculty of Information and Communication Technology**  
**ITCS225 Principles of Operating Systems**  
**Mahidol University**  

---

## 🧠 1.1 Project Overview

### 🎯 Objective:
To **optimize data analysis and visualization** using **efficient system-level operations** and **performance comparisons** based on OS principles.

---

### 🧩 Core Operating System Concepts Applied

- **🧵 Process Scheduling**  
  Utilized `multiprocessing` to parallelize tasks such as reading CSVs and rendering visualizations.

- **💾 Memory Management**  
  Used `psutil` to monitor memory usage before and after key operations.

- **📂 File I/O**  
  Benchmarked multiple file read/write methods:
  - Reading: `pandas`, `mmap`, and `buffered reading`
  - Writing: `pandas CSV`, `buffered writing`, and `parquet format`

---

### ⚙️ Implementation Highlights

- Modular codebase: split into data loading, system monitoring, and visualization.
- Real-time logging of CPU and memory usage per process.
- Clean, readable code with error handling for system-level functions.

---

### 🚀 Performance Optimization

#### 🧪 File Method Benchmarks

- **Reading Techniques**:
  - `pandas.read_csv()`
  - `mmap` memory-mapped read
  - Buffered line-by-line read

- **Writing Techniques**:
  - `pandas.to_csv()`
  - Buffered file write
  - Parquet (columnar storage)

📈 Comparison visualizations generated:
- `performance_comparison.png`
- `write_speed_comparison.png`

---

### 📊 Visualization Techniques

- Heatmaps created using:
  - **Seaborn**
  - **Altair**

- Measured:
  - Execution time
  - CPU usage
  - Memory consumption

🧾 Results summary table included in report for easy reference.

---

### ✅ Results Snapshot

- **Buffered read** was the fastest read method.
- **Parquet format** yielded best performance for writing large datasets.
- **Altair** provided faster rendering with lower memory usage than Seaborn.

---

### 🏁 Outcome

This project demonstrates how **core OS principles** can significantly improve **data analysis performance** and deliver a system that is:
- Robust
- Modular
- Efficient
- Backed by visual and numeric benchmarks

---

## 🗂 1.2 Dataset

**Dataset Name:** *Student Stress Factors: A Comprehensive Analysis*  
📎 [View on Kaggle](https://www.kaggle.com/datasets/rxnach/student-stress-factors-a-comprehensive-analysis)  

- Format: CSV  
- Approx. 1,500 entries  
- Source: Publicly available dataset from Kaggle

---

## 📝 1.3 Data Description

This dataset explores the **multifaceted causes of student stress**, including:

- Sleep quality
- Physiological health
- Psychological wellness
- Academic performance
- Social interaction

These features enable an **in-depth correlation analysis** and the discovery of **hidden subgroups** based on student behavior and health indicators.

---

## 👨‍💻 Team Members

| Student ID | Name                          |
|------------|-------------------------------|
| 6688030    | Sarach Islam                  |
| 6688055    | Takka Leeheng                 |
| 6688059    | Athip Madnoth                 |
| 6688124    | Nithit Teeraworawit           |
| 6688173    | Passakorn Piboonmahachotikul  |

---

## 🎓 Presented To

**Lect. Ph.D. Kanoksak Wattanachote**  
ITCS225 Principles of Operating Systems  
Mahidol University  
🗓️ *29 April 2025*

---

