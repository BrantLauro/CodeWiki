<h1 align="center">CodeWiki 📚🌐</h1>

<h2 align="center">
    A CLI-based Search Engine for Tech Data ⚙️<br>
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/YourUsername/CodeWiki?style=social">
    <img alt="GitHub followers" src="https://img.shields.io/github/followers/BrantLauro?label=Follow%20me&style=social">
</h2>
<p align="center">
    <img alt="softbus" src="https://github.com/user-attachments/assets/086c2fa1-49cb-4101-8f97-84f801ce56e1">
</p>

## 💡 Description

**CodeWiki** is a command-line search engine developed in **C** as an educational project for the **Algorithms and Data Structures II** course. It allows users to compare the efficiency of hash table lookups and binary search on a dataset of technologies and programming languages.

The program reads a `.csv` file containing records about technologies and builds a hash table using the name of each technology as the key. The system tracks the number of comparisons required for both binary search and hash methods, offering a clear comparison of performance.

## ⚙️ Features

- Import technology data from a `.csv` file
- Create a hash table from the data using string keys
- Perform:
  - Binary search
  - Hash table search (with chaining via linked lists)
- Return formatted results with complete tech information
- Count and compare the number of accesses per search method
- Clean and user-friendly CLI interface

## 🔧 Tech Stack

- **C Programming Language**
- **File I/O (CSV and TXT)**
- **Command-line Interface (CLI)**
- **Hash Tables with Linked Lists**
- **Binary Search Algorithms**

## 🚀 Installation

[Click Here](https://github.com/BrantLauro/CodeWiki/releases/) to download.
- Important:
  - If you want to use the **precompiled** `.exe`, make sure to also download the `dados.txt` file and place it in the same folder as the executable.
  - If you prefer to **compile the project yourself**, download the `pldb.csv` file and **uncomment line 39** in `main.c`.
    -  When you run the program with that line active, it will generate a dados.txt file containing the hash table for all the data.
    - After generation, you can **comment line 39 again**, recompile the code, and you're ready to search for most technologies using the hash search method.

## 👨‍💻 Contributors

### Lauro Brant ([BrantLauro](https://github.com/BrantLauro))  
Information Systems Student - Unimontes

### Thiago Rezende ([thiagorezendev](https://github.com/thiagorezendev))  
Information Systems Student - Unimontes

## ©️ Copyrights

This project is licensed under the MIT License.

---

> LinkedIn [Lauro Brant](https://www.linkedin.com/in/lauro-brant-4858861b3/) &nbsp;&middot;&nbsp;
> GitHub [BrantLauro](https://github.com/BrantLauro) &nbsp;

> LinkedIn [Thiago Rezende](https://www.linkedin.com/in/thiago-rezende-398707248/) &nbsp;&middot;&nbsp;
> GitHub [thiagorezendev](https://github.com/thiagorezendev) &nbsp;
