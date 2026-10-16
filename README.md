# SANREMES • Python Architecture Series

**S1 / EP1 – Python Is NOT an Interpreted Language**

Dissecting `.pyc`, `__pycache__`, and CPython Bytecode.

## About this episode

This is the first episode of the **SANREMES Python Architecture Series**.

We prove that Python is **compiled to bytecode** (not purely interpreted line-by-line) by examining:

- The real CPython execution pipeline (AST → Code Object → PVM)
- Why single scripts don’t always create `.pyc` files
- Generating `__pycache__` via module imports
- The 16-byte `.pyc` header (magic number, PEP 552, timestamp)
- Marshalled code objects
- Live disassembly with `dis.dis()`
- Python 3.14 super-instructions (`LOAD_FAST_BORROW_LOAD_FAST_BORROW`)

## YouTube

The final polished video is ready for upload.

**Suggested timestamps:**

```
0:00 - The "Python is Interpreted" Myth
0:58 - Proof #1: The 4-Line Syntax Trap (Compilation vs Execution)
2:05 - The Real CPython Execution Pipeline (AST to PVM)
2:42 - Why Single Scripts Don't Create .pyc Files
3:03 - Proof #2: Generating __pycache__ & .pyc via Module Imports
3:58 - Cracking Open .pyc in VS Code Hex Editor
4:47 - Anatomy of the 16-Byte .pyc Header (Magic Number, PEP 552, Timestamp)
5:22 - Verifying CPython's Magic Number Live in IDLE
7:06 - Inside the Marshalled Code Object (0xE3)
7:42 - Proof #3: Disassembling Bytecode Live with dis.dis()
8:13 - Python 3.14 Super-Instructions (LOAD_FAST_BORROW_LOAD_FAST_BORROW)
9:31 - Summary & What's Next in Episode 02
```

## Series

**SANREMES • AI FROM BASICS TO EVERYTHING**

Next Episode: How Python Runs Your Code — PVM Stack Architecture & Evaluation Loop.
