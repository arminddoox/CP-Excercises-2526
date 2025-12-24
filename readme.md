# About

Competitive programming (CP) practice and self-training at HUST, 2025-2026.

# Setup C++ with vscode

> Copy these instructions to GPT for details.

### 0. Install C/C++ Extension Pack

### 1. Open vscode instruction "Get started with C++...":
Navigate to &rarr; "Help" &rarr; "Open Walkthrough..." &rarr; Search "c++" &rarr; Enter.

### 2. Follow instructions
  <details>
  <summary><b>summary</b></summary>
    
  * run the suggested bash code &rarr; install vs-build-tools.
  * open "developer command prompt" (or search "dev..." in window-search).
  * 
  * To get started, create a `.cpp` file then `F5` & Enter for auto-build &rarr; have `.vscode` folder.
  * `F5`(with debug) / `Ctrl+F5`(without debug) to run file.
  * Create other `.cpp` file &rarr; `F5` &rarr; choose "C++ (Windows)" _if possible_.
  * 
  * In another way to get started, with terminal, don't need `.vscode` folder.
  * Initially, create a `.cpp` file then run bash `cl file-name.cpp` then bash `.\file-name.exe` to run file. 
  * Create other `.cpp` file &rarr; bash `cl file-name.cpp` &rarr; bash `.\file-name.exe`.

  </details>

# Libraries

### 1. `<bits/stdc++.h>`

Create `bits` folder &rarr; `stdc++.h` file inside &rarr; copy-paste **abridged version** &rarr; `#include <bits/stdc++.h>` in `.cpp` file.
* <details>
  <summary><b>summary</b></summary>

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

### 2. `C 17`
* <details>
  <summary><b>summary</b></summary>

  ```c
  ///utilities
  #include <stdio.h>
  #include <stdlib.h>
  #include <assert.h>
  ///string, char, bool
  #include <string.h>
  #include <ctype.h>
  #include <stdbool.h>
  ///math
  #include <math.h>
  #include <float.h>
  #include <limits.h>
  #include <stdint.h>
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
