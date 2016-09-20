# Python3 vs ES2016 cheatsheet
### Comparison of features for learning

---
Task | Python 3 | ES2016
--- | --- | ---
**Assignment** | | 
Variables | `y = 1` | `var y = 1;`
Constants | `Y = 1` | `const Y = 1;`
Many at once | `x = 1; y = 2` | `var x = 1, y = 2;`
with unpacking / destructuring | `x, y = y, x` | `var [x, y] = [1, 2];` 
**unpacking** | | 
Swap | `x, y = y, x` | `[x, y] = [y, x]`;
First & Rest | `head, *rest = xs` | `[head, ...rest] = xs` 
First, Last, Middle | `head, *middles, tail = xs` |
**functional Programming** | | 
lambdas | `lambda x: x + 1` | `x => x + 1;`
multiple parameters | `lambda x, y: x + y` | `(x, y) => x + y;`
