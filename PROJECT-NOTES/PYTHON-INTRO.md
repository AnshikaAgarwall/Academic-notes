1️⃣ PYTHON BASICS (Core Rules & Tricks)
🔹 Python Characteristics
Interpreted → executes line by line
Dynamically typed → no datatype declaration
Case-sensitive → Var ≠ var
Indentation = block (no {})


🔹 Keywords
Reserved words: if, else, for, while, True, False, None
Cannot be used as identifiers
LIBRARY USED:
import keyword
keyword.kwlist

🔹 Input / Output
x = input("Enter: ")   # Always string
print(x)
EXAM TRAP:
input() returns string, not int


DATA TYPES-------------------------
| Type    | Example  | Mutable? |
| ------- | -------- | -------- |
| int     | 10       | ❌        |
| float   | 3.14     | ❌        |
| complex | 2+3j     | ❌        |
| str     | "hi"     | ❌        |
| list    | [1,2]    | ✅        |
| tuple   | (1,2)    | ❌        |
| set     | {1,2}    | ✅        |
| dict    | {1: "a"} | ✅        |
| bool    | True     | ❌        |



-----------------------PYTHON OPERATORS – TABLE WITH EXAMPLES--------------------------------------
1️⃣ Arithmetic Operators

| Operator | Name           | Example  | Output |
| -------- | -------------- | -------- | ------ |
| `+`      | Addition       | `5 + 3`  | `8`    |
| `-`      | Subtraction    | `5 - 3`  | `2`    |
| `*`      | Multiplication | `5 * 3`  | `15`   |
| `/`      | Division       | `5 / 2`  | `2.5`  |
| `//`     | Floor Division | `5 // 2` | `2`    |
| `%`      | Modulus        | `5 % 2`  | `1`    |
| `**`     | Exponent       | `2 ** 3` | `8`    |

2️⃣ Relational (Comparison) Operators
| Operator | Meaning          | Example  | Output  |
| -------- | ---------------- | -------- | ------- |
| `==`     | Equal to         | `5 == 5` | `True`  |
| `!=`     | Not equal        | `5 != 3` | `True`  |
| `>`      | Greater than     | `5 > 3`  | `True`  |
| `<`      | Less than        | `5 < 3`  | `False` |
| `>=`     | Greater or equal | `5 >= 5` | `True`  |
| `<=`     | Less or equal    | `5 <= 3` | `False` |

3️⃣ Assignment Operators
| Operator | Description       | Example   | Result    |
| -------- | ----------------- | --------- | --------- |
| `=`      | Assign            | `x = 5`   | `x = 5`   |
| `+=`     | Add & assign      | `x += 3`  | `x = 8`   |
| `-=`     | Subtract & assign | `x -= 2`  | `x = 3`   |
| `*=`     | Multiply & assign | `x *= 2`  | `x = 10`  |
| `/=`     | Divide & assign   | `x /= 2`  | `x = 2.5` |
| `//=`    | Floor & assign    | `x //= 2` | `x = 2`   |
| `%=`     | Modulus & assign  | `x %= 2`  | `x = 1`   |

4️⃣ Logical Operators
| Operator | Meaning   | Example          | Output  |
| -------- | --------- | ---------------- | ------- |
| `and`    | Both true | `True and False` | `False` |
| `or`     | Any true  | `True or False`  | `True`  |
| `not`    | Reverse   | `not True`       | `False` |

5️⃣ Bitwise Operators (Important for MCQs)
| Operator | Name        | Example  | Output |    |     |
| -------- | ----------- | -------- | ------ | -- | --- |
| `&`      | AND         | `5 & 3`  | `1`    |    |     |
| `        | `           | OR       | `5     | 3` | `7` |
| `^`      | XOR         | `5 ^ 3`  | `6`    |    |     |
| `~`      | NOT         | `~5`     | `-6`   |    |     |
| `<<`     | Left Shift  | `5 << 1` | `10`   |    |     |
| `>>`     | Right Shift | `5 >> 1` | `2`    |    |     |

6️⃣ Membership Operators
| Operator | Meaning     | Example              | Output |
| -------- | ----------- | -------------------- | ------ |
| `in`     | Present     | `'a' in 'apple'`     | `True` |
| `not in` | Not present | `'x' not in 'apple'` | `True` |

7️⃣ Identity Operators
| Operator | Meaning          | Example      | Output         |
| -------- | ---------------- | ------------ | -------------- |
| `is`     | Same object      | `a is b`     | `True / False` |
| `is not` | Different object | `a is not b` | `True / False` |


===== Exam Trick=====
== → checks value
is → checks memory location

8️⃣ Unary Operators
| Operator | Meaning     | Example | Output |
| -------- | ----------- | ------- | ------ |
| `+`      | Unary plus  | `+5`    | `5`    |
| `-`      | Unary minus | `-5`    | `-5`   |


-------------IMPORTANT HIGHLIGHTS---------------

/ always returns float
// returns integer
is should not be used for value comparison
Bitwise operators work on binary
