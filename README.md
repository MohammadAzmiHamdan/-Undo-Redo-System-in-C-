# Undo/Redo System in C++

A simple **Undo/Redo system implemented in C++ using two stacks**.

This project demonstrates a practical application of the **Stack Data Structure** for managing previous and future states of a value.

## Overview

The `ClsMyString` class manages a string value and provides:

- Setting a new value
- Getting the current value
- Undoing previous changes
- Redoing undone changes

The implementation uses two stacks:

```cpp
stack<string> _Undo;
stack<string> _Redo;
