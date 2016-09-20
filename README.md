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
**Unpacking** | | 
Swap | `x, y = y, x` | `[x, y] = [y, x]`;
First & Rest | `head, *rest = xs` | `[head, ...rest] = xs` 
First, Last, Middle | `head, *middles, tail = xs` |
**IO | | 
print | `print(x)` | `console.log(x);` 
interpolation aka template strings | `f'my age is {age + 1}'` | `` `my age is ${age + 1}` `` 
**Functional Programming** | | 
lambdas | `lambda x: x + 1` | `x => x + 1;`
multiple parameters | `lambda x, y: x + y` | `(x, y) => x + y;`
bind to var | `f = lambda x: x + 1` | `var f = x => x + 1;`
map | squares = `map(square, xs)` | `oe;`
