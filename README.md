# Python3 vs ES2016 cheatsheet
### Comparison of features for learning

---
Task | Python 3 | ES2016 | Notes
--- | --- | --- | ---
**Assignment** | | 
Variables | `y = 1` | `var y = 1;`
Constants | `Y = 1` | `const Y = 1;`
Many at once | `x = 1; y = 2` | `var x = 1, y = 2;`
unpacking / destructuring | `x, y = y, x` | `var [x, y] = [1, 2];` 
**Unpacking / spread** | | 
Swap | `x, y = y, x` | `[x, y] = [y, x]`;
First & Rest | `head, *rest = xs` | `[head, ...rest] = xs` 
First, Last, Middle | `head, *middles, tail = xs` |
**Comparison** | |
chained comparisons | `1 < x <= 9` | `1 < x && x <= 9` | left associative in JS
ternary | `x if pred else y` | `pred ? x : y;`
truthiness | `if x` | `if (x)` | JS: bool, int, float, str only
**Math** | | 
exponents | `x **= y ** z` | `x **= y ** z;` | ES2016
int division  | `x // y` | `Math.floor(x / y);` | 
increments | `x += 1; x -= 1` | `x ++; x--;`
**Arrays / Lists** |  | 
length | `len(xs)` | `xs.length`
slicing  | `xs[start:end:step]` | `xs.slice(start, [end]);` | 
any / some | `any(map(pred, xs))` | `xs.some(pred)` | for some predicate
all / every | `all(map(pred, xs))` | `xs.every(pred)` | sim
existance | `x in xs` | `xs.includes(x)` | ES2016
**Loops** | |
for each | `for x in xs:` | `for (x in xs){}` |
enumerate | `for i, x in enumerate(xs):` | `xs.forEach((x, i) => ...)`
**IO** | | c
print | `print(x)` | `console.log(x);` 
interpolation | `f'my age is {age + 1}' \` | `` `my age is ${age + 1} `` 
aka template strings | `'years old'` |  `` years old` ``
**Functional** | | 
unary lambdas | `lambda x: x + 1` | `x => x + 1;`
nullary | `lambda : 1` | `() => 1;`
multi-airy | `lambda x, y: x + y` | `(x, y) => x + y;`
bind to var | `f = lambda x: x + 1` | `var f = x => x + 1;`
map | `sqrs = map(square, xs)` | `sqrs = xs.map(square);`
filter | `odds = filter(is_odd, xs)` | `odds = xs.filter(is_odd);`
reduce | `sum = reduce(add, xs)` | `sum = xs.reduce(add);` | py: from functools import reduce
  | `` | `;` | 
  | `` | `;` | 
  | `` | `;` | 
  | `` | `;` | 
  | `` | `;` | 
  | `` | `;` | 
  | `` | `;` | 
  | `` | `;` | 
