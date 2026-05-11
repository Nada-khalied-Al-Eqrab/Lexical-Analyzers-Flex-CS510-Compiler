# Lexical Analyzers Flex -  Compiler Construction  (CS510) Lab 
A repository dedicated to practical implementations and lab work for the **Compiler Construction (CS510)** course. This project contains applications of theoretical compiler concepts with a primary focus on **Lexical Analysis** using **Flex**.

#  Repository Content

##  Lexical Analyzers
`.l` files designed to recognize different types of tokens such as:
- Keywords
- Identifiers
- Operators
- Numbers
- Special Symbols

##  Automata Implementations
Implementations and solutions related to:
- NFA (Nondeterministic Finite Automata)
- DFA (Deterministic Finite Automata)
- DFA Minimization Algorithms

##  Assignments & Sheets
Solutions for:
- Lab assignments
- Lecture sheets and exercises

---

# Tools Used

- **Flex** — Fast Lexical Analyzer Generator
- **C / C++**
- **GCC Compiler**

---

# 🚀 How to Run

To execute any Flex (`.l`) file in this repository, follow these steps in the terminal:

## 1- Generate the C File

```bash
flex filename.l
```

---

## 2- Compile the Generated File Using GCC

```bash
gcc lex.yy.c -o scanner -lfl
```

---

## 3- Run the Lexical Analyzer

```bash
./scanner
```

---

#  Notes

- DFA Minimization rules were considered to improve scanner efficiency and reduce unnecessary states.
- The projects cover:
  - Dead States
  - Transition Validation
  - Correct Arrow Directions
- All implementations are based on concepts explained in both lectures and lab sessions of the **Compiler Construction** course.
- This repository serves as a personal reference for practicing and understanding compiler construction concepts practically.

---

#  Suggested `.gitignore`

To keep the repository clean and avoid uploading temporary or generated files, create a `.gitignore` file and add the following lines:

```gitignore
*.exe
lex.yy.c
scanner
```

---

#  Support

If you find this repository helpful, don't forget to:

```bash
⭐ Star the Repository
```

---

#  Author

Developed for learning and practicing concepts of: Nada Al-Eaqrab

**Compiler Construction (CS510)** 🚀
