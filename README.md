# Mini C Compiler

A **Mini C → MIPS compiler** implemented in **C++**, supporting full compilation from source code to executable assembly through **lexical analysis, parsing, semantic analysis, and code generation**.

> 📩 **Source Code Access:**
> **Please email andy.bukovcan@uwaterloo.ca to access the code.**

---

## 🚀 Features

* **End-to-end compilation pipeline**: Mini C → MIPS assembly
* **Lexical analysis (Scanner)** — tokenization using DFA-based pattern matching
* **Parsing** — bottom-up **SLR(1)** parsing using context-free grammars
* **Semantic analysis** — scope resolution, type checking, and symbol table management
* **Code generation** — emits optimized **MIPS assembly**
* **Robust error handling** — detects lexical, syntax, and semantic errors

---

## 🛠 Compiler Pipeline

```
Mini C Source
     ↓
Scanner (Tokenization)
     ↓
Parser (SLR(1) CFG Parsing)
     ↓
Semantic Analysis (Type + Scope Checking)
     ↓
Code Generation
     ↓
MIPS Assembly Output
```

---

## 🧠 Technical Highlights

* Implemented **DFA-based maximal munch scanning**
* Built a **custom SLR(1) parser** using parse tables
* Designed **symbol tables** for scope + type resolution
* Implemented **stack-frame management and register allocation** for MIPS codegen
* Structured compiler passes for **modularity and testability**

---

## 📦 Language Support

The compiler supports a subset of C including:

* Functions & procedures
* Integer arithmetic
* Conditionals
* Loops
* Pointers & arrays
* Stack-based memory management

---
