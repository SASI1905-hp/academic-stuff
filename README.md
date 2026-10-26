<div align="center">

# 📚 Academic Stuff

**My college lab programs in C, C++, Python, DBMS, data structures and the MERN stack, organised by subject.**

![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)

![Made for learning](https://img.shields.io/badge/Made%20for-Learning-brightgreen)
![Last commit](https://img.shields.io/github/last-commit/SASI1905-hp/academic-stuff?color=blue)
![Repo size](https://img.shields.io/github/repo-size/SASI1905-hp/academic-stuff?color=orange)
[![Discussions](https://img.shields.io/badge/Ask-Discussions-blue?logo=github)](https://github.com/SASI1905-hp/academic-stuff/discussions)

</div>

A growing collection of programs written while studying B.Tech (Artificial Intelligence and Machine Learning) at Aditya University. Each folder holds the programs for one subject, so you can browse by topic, read the code and run it yourself.

## 📑 Table of Contents

- [What's Inside](#-whats-inside)
- [Repository Structure](#-repository-structure)
- [Prerequisites](#-prerequisites)
- [How to Run the Programs](#-how-to-run-the-programs)
- [Naming Conventions](#-naming-conventions)
- [Found a Mistake or Have a Question?](#-found-a-mistake-or-have-a-question)
- [Academic Integrity](#️-academic-integrity)
- [Author](#-author)

## 📦 What's Inside

| Folder | Subject | Language / Stack |
|---|---|---|
| [`C_Programs`](C_Programs) | Practice programs in C, such as pattern printing | C |
| [`CPP_Programs`](CPP_Programs) | Practice programs in C++ | C++ |
| [`Python_Programs`](Python_Programs) | Practice programs in Python | Python |
| [`DBMS_Programs`](DBMS_Programs) | Database management system lab programs | SQL |
| [`datastructures`](datastructures) | Data structure implementations | Mixed |
| [`mern_programs`](mern_programs) | Weekly web development lab programs | MongoDB, Express, React, Node.js |

## 🗂️ Repository Structure

```
academic-stuff/
├── C_Programs/         # C practice programs
├── CPP_Programs/       # C++ practice programs
├── Python_Programs/    # Python practice programs
├── DBMS_Programs/      # SQL scripts for the DBMS lab
├── datastructures/     # Data structure implementations
├── mern_programs/      # MERN stack lab programs, organised week by week
└── README.md
```

## 🧰 Prerequisites

You only need the tools for the folder you want to try.

| To run | Install |
|---|---|
| C or C++ | [GCC / G++](https://gcc.gnu.org/) |
| Python | [Python 3](https://www.python.org/downloads/) |
| DBMS | Any SQL client, such as [MySQL](https://dev.mysql.com/downloads/) |
| MERN | [Node.js](https://nodejs.org/) (includes npm) and [MongoDB](https://www.mongodb.com/try/download/community) or a free [MongoDB Atlas](https://www.mongodb.com/atlas) cluster |

## ▶️ How to Run the Programs

Clone the repository first:

```bash
git clone https://github.com/SASI1905-hp/academic-stuff.git
cd academic-stuff
```

**C programs**

```bash
gcc C_Programs/program_name.c -o program
./program          # Windows: program.exe
```

**C++ programs**

```bash
g++ CPP_Programs/program_name.cpp -o program
./program          # Windows: program.exe
```

**Python programs**

```bash
python Python_Programs/program_name.py
```

**DBMS programs**

Open the script in your database client and run it from top to bottom. Create the tables before running queries that use them.

**MERN programs**

Open the folder for the week you want and install its dependencies before running it:

```bash
cd mern_programs/week-folder-name
npm install
npm start          # or: node file_name.js, depending on the program
```

Programs that use MongoDB need a running database. Start MongoDB locally, or put your Atlas connection string in a `.env` file. Never commit real credentials to the repository.

> Replace `program_name` and `week-folder-name` with the real names. If a program asks for input, type it in the terminal when prompted.

## 🏷️ Naming Conventions

- Folders are named by subject (`C_Programs`, `Python_Programs`, and so on).
- File names use lowercase words joined by underscores, for example `basic_pattern_3_4.c`.
- C, C++, Python and DBMS programs are stand-alone and do not need other files to run.
- `mern_programs` is organised by week, and each week's folder is self-contained with its own dependencies.

## 💬 Found a Mistake or Have a Question?

- **Spotted a bug or broken link?** [Open an issue](https://github.com/SASI1905-hp/academic-stuff/issues/new/choose) and pick *Report a mistake or broken link*.
- **Want a new topic added?** Pick *Request new material* in the same place.
- **Just have a question?** Start a thread in [Discussions](https://github.com/SASI1905-hp/academic-stuff/discussions).
- **Want to contribute a fix?** Fork the repo, make your change, and open a pull request. A short checklist appears automatically.

## ⚖️ Academic Integrity

These programs are shared for learning and reference. Read them, run them and try changes, but write your own solutions for assignments and exams. Copying code for graded work can break your institution's academic integrity policy.

## 👤 Author

**Konda Sasi Meghana**, Department of Artificial Intelligence and Machine Learning, Aditya University.

GitHub: [@SASI1905-hp](https://github.com/SASI1905-hp)

<div align="center">

If this repository helps you, consider giving it a ⭐

[⬆ Back to top](#-academic-stuff)

</div>
