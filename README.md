# ⚙️ C-Forge — Experimental C Compiler (Discontinued)

> A deep dive into compiler construction from scratch — written in C.  
> This project was my personal attempt to build a C compiler, walking through every critical phase including lexical analysis, parsing, type checking, and early disagreement (disaguring) stage.

---

## ❗ Status: **Discontinued**

This project was discontinued due to shift in priorities, but remains a solid foundation and educational resource.  
I reached as far as:

- ✅ **Lexer**  
- ✅ **Parser**  
- ✅ **Type Checker**  
- ⚠️ **Disaguring** (partial implementation — IR design & codegen prep)

---

## 🧱 Components Implemented

| Component | Description |
|----------|-------------|
| Lexer | Tokenizes source code using manual state-machine logic |
| Parser | Builds AST for expressions, conditionals, and function definitions |
| Type Checker | Performs semantic validation and reports mismatches |
| Symbol Table | Partially built symbol management |
| IR Planning | Early steps toward generating intermediate representation (disaguring phase) |

---

