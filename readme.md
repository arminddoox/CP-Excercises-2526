# About

Đây là các bài tập lập trình thi đấu (CP) đã hoàn thành trong kỳ HUST20251, được lưu trên GitHub để thuận tiện cho việc lập trình từ xa.

This repository contains the competitive programming (CP) exercises in HUST20251 semester, saved for easy remote access.

# How to use this repo

Open vscode &rarr; navigate to "Terminal" &rarr; "New Terminal".

```bash
git clone https://github.com/arminddoox/CP-Excercises-20251.git
git pull origin main

---(optional)---
git init
git remote add origin https://github.com/arminddoox/CP-Excercises-20251.git
git pull origin main --force
git fetch origin
git reset --hard origin/main
``` 

# How to setup C++ originally with vscode

> Copy these instructions to GPT for details.

### 0. Install C/C++ Extension Pack

### 1. Open vscode instruction "Get started with C++...":
Navigate to &rarr; "Help" &rarr; "Open Walkthrough..." &rarr; Search "c++" &rarr; Enter.

### 2. Please follow instructions
  <details>
  <summary>summary & note</summary>
    
  * run the suggested bash code &rarr; install vs-build-tools.
  * open "developer command prompt" (or "dev..." in window-search).
  * 
  * To get started, create a `.cpp` file then `F5` & Enter for auto-build &rarr; have `.vscode` folder.
  * `F5`(with debug) / `Ctrl+F5`(without debug) to run file.
  * Create other `.cpp` file &rarr; `F5` &rarr; choose "C++ (Windows)" _if possible_.
  * 
  * In another way to get started, with terminal, don't need `.vscode` folder.
  * Initially, create a `.cpp` file then run bash `cl file-name.cpp` then bash `.\file-name.exe` to run file. 
  * Create other `.cpp` file &rarr; bash `cl file-name.cpp` &rarr; bash `.\file-name.exe`.

  </details>

### 3. `<bits/stdc++.h>`

Create `bits` folder &rarr; `stdc++.h` file inside &rarr; copy-paste **abridged version** &rarr; `#include <bits/stdc++.h>` in `.cpp` file.
* <details>
  <summary><b>abridged version</b></summary>

  ```cpp
  // basic
  #include <iostream>
  #include <string>
  #include <cstdio>
  #include <cstring>
  // stl
  #include <vector>
  #include <deque>
  #include <list>
  #include <stack>
  #include <queue>
  #include <map>
  #include <set>
  #include <unordered_map>
  #include <unordered_set>
  #include <bitset>
  // algorithm
  #include <algorithm>
  #include <numeric>
  #include <functional>
  // utility
  #include <utility>
  #include <tuple>
  #include <iterator>
  // math
  #include <cmath>
  #include <cstdlib>
  ```

  </details>

</br>

GCC builtins vs MSVC intrinsics(`#include <intrin.h>`)
* | GCC Builtin               | MSVC Intrinsic  |
  | ------------------------- | --------------- |
  | `__builtin_popcount(x)`   | `__popcnt(x)`   |
  | `__builtin_popcountll(x)` | `__popcnt64(x)` |
  | `__builtin_clz(x)`        | `_lzcnt_u32(x)` |
  | `__builtin_ctz(x)`        | `_tzcnt_u32(x)` |
