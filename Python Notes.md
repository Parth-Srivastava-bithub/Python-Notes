## ✅ **1. Introduction to Programming**

---

### ❓ *Q: What is Programming?*

---

### 📘 Hinglish Explanation (Detail mein):

**Programming ka matlab hota hai computer ko step-by-step instructions dena.**
Jaise tum kisi ko recipe batate ho, waise hi computer ko batate ho ki kya aur kaise karna hai.

**Kyu karte hai programming?**

* Computer se kaam karwane ke liye
* Software, apps, websites banane ke liye
* Real-world problems solve karne ke liye

**Programming se kya kar sakte ho?**

* Game development
* Web/app development
* Automation
* Data analysis, AI, Machine Learning

---

### 📌 Real-life Example:

Tumhara alarm app subah 7 baje bajta hai — woh programming se hi possible hai. Kisi ne program likha jo time check karta hai aur exact moment pe alarm play karta hai.

---

### 🧑‍💻 Code Example:

```python
# Simple program to print something
print("Hello, World!")
```

**Output:**

```
Hello, World!
```

---

### 🧠 Summary in English:

Programming is the process of writing instructions for a computer to perform tasks.
Used to build apps, websites, games, and much more.

---

## ✅ **2. The Basic Model of Computation**

---

### ❓ *Q: What is the Basic Model of Computation?*

---

### 📘 Hinglish Explanation (Detail mein):

**Model of Computation ka matlab hota hai ek theoretical framework jo batata hai computer kisi problem ko kaise solve karta hai.**
Matlab: Input lo ➡ Processing karo ➡ Output do.

**Components:**

* **Input:** Jo data diya gaya (e.g., user ka number)
* **Processing:** Logic ya calculation (e.g., number \* 2)
* **Output:** Final result (e.g., 10 ka double = 20)

---

### 📌 Real-life Example:

Calculator mein tum 5 + 3 karte ho.

* Input: 5, 3
* Processing: Addition
* Output: 8

---

### 🧑‍💻 Code Example:

```python
num = 5
result = num * 2
print(result)
```

**Output:**

```
10
```

---

### 🧠 Summary in English:

Basic Model of Computation involves 3 steps:
**Input → Processing → Output**
It’s a fundamental way computers solve problems.

---

## ✅ **3. Algorithms**

---

### ❓ *Q: What is an Algorithm?*

---

### 📘 Hinglish Explanation (Detail mein):

**Algorithm ek step-by-step procedure hota hai jo kisi problem ka solution deta hai.**
Bilkul ek recipe ki tarah — pehle kya karna hai, baad mein kya — sab defined hota hai.

**Features:**

* Clear steps
* Finite steps (kabhi infinite loop nahi hona chahiye)
* Definite output

---

### 📌 Real-life Example:

Chai banane ki recipe bhi ek algorithm hai:

1. Paani garam karo
2. Chai patti daalo
3. Doodh daalo
4. Chai chhano
5. Serve karo

---

### 🧑‍💻 Code Example:

```python
# Algorithm to find square of a number
num = 4
square = num * num
print(square)
```

**Output:**

```
16
```

---

### 🧠 Summary in English:

An algorithm is a well-defined sequence of steps used to solve a problem or perform a task.

---

## ✅ **4. Flowcharts**

---

### ❓ *Q: What is a Flowchart?*

---

### 📘 Hinglish Explanation (Detail mein):

**Flowchart ek diagram hota hai jo kisi process ya algorithm ko visually dikhata hai.**
Arrows, boxes, diamonds ka use karke steps ko represent karte hain.

**Flowchart ka fayda:**

* Logic easily samajh aata hai
* Debug karna asaan hota hai
* Planning mein madad milti hai

---

### 📌 Real-life Example:

Bank ATM process:

* Start
* Card insert karo
* PIN enter karo
* Amount choose karo
* Cash nikaalo
* End

---

### 🧠 Code Not Needed — Visual hota hai!

But, you can imagine flow like:

```
[Start]
   |
[Enter Number]
   |
[Multiply by 2]
   |
[Print Result]
   |
[End]
```

---

### 🧠 Summary in English:

Flowchart is a **visual representation of an algorithm** using symbols to show steps and their order.

---

## ✅ **5. Programming Languages**

---

### ❓ *Q: What are Programming Languages?*

---

### 📘 Hinglish Explanation (Detail mein):

**Programming Language ek medium hota hai jiske through hum computer se baat karte hain.**
Jaise humans Hindi/English bolte hain, waise computer Python, Java, C++ etc. "samajhta" hai.

**Types:**

* **Low-level:** Close to machine (Assembly)
* **High-level:** Easy to understand (Python, Java)

---

### 📌 Real-life Example:

Tum Python mein likhte ho:

```python
print("Namaste Duniya")
```

Computer isse binary mein convert karke kaam karta hai.

---

### 🧠 Summary in English:

Programming languages allow humans to write instructions for computers. Popular examples include Python, C++, Java, etc.

---

## ✅ **6. Compilation**

---

### ❓ *Q: What is Compilation?*

---

### 📘 Hinglish Explanation (Detail mein):

**Compilation ek process hota hai jisme humara code (high-level language) machine code (0s & 1s) mein convert hota hai.**
Jo bhi likhte ho (e.g., C/C++ code), usko computer ko samajhne layak banaya jata hai.

**Compiler:** Wo software hota hai jo ye conversion karta hai.

---

### 📌 Real-life Example:

Tumne likha:

```c
printf("Hello");
```

Compiler usko binary code mein convert karta hai taaki machine usse run kar sake.

---

### 🧠 Summary in English:

Compilation is the process of converting source code into machine code using a compiler so that the computer can execute it.

---

## ✅ **7. Testing & Debugging**

---

### ❓ *Q: What is Testing and Debugging?*

---

### 📘 Hinglish Explanation (Detail mein):

**Testing:** Program ka output check karna — sahi aa raha hai ya nahi.
**Debugging:** Agar koi error aayi, toh usse fix karna.

Ye dono steps bahut important hote hain program reliable banane ke liye.

---

### 📌 Real-life Example:

Agar tumhara calculator app 2 + 2 = 5 dera hai, toh:

* **Testing** se error detect hoga
* **Debugging** se error fix hoga

---

### 🧑‍💻 Code Example:

```python
# Buggy code
a = 10
b = 0
# print(a / b)  # This will throw error: division by zero
```

**Debugging solution:**

```python
if b != 0:
    print(a / b)
else:
    print("Cannot divide by zero")
```

---

### 🧠 Summary in English:

**Testing** ensures the program works as expected.
**Debugging** is the process of identifying and fixing errors in the code.

---

## ✅ **8. Documentation**

---

### ❓ *Q: What is Documentation in Programming?*

---

### 📘 Hinglish Explanation (Detail mein):

**Documentation ka matlab hota hai code ke baare mein likhna — kya karta hai, kaise use karna hai, kis logic pe kaam kar raha hai.**
Ye doosre developers (ya tum khud future mein) ke liye helpful hota hai.

---

### 📌 Real-life Example:

Tumne ek function banaya jo discount calculate karta hai. Uske upar comment likhna:

```python
# Ye function product ka discount calculate karta hai
def calculate_discount(price, percent):
    return price * (percent / 100)
```

---

### 🧠 Summary in English:

Documentation is the written explanation of how the code works, what it does, and how to use it. It helps in maintenance and collaboration.

---

## ✅ **9. Flowchart Symbols**

---

### ❓ *Q: What are the basic symbols used in Flowcharts?*

---

### 📘 Hinglish Explanation (Detail mein):

Flowchart banane ke liye kuch **standard symbols** use hote hain jo kisi bhi process ke different parts ko dikhate hain.

| Symbol | Name                             | Use                                    |
| ------ | -------------------------------- | -------------------------------------- |
| 🔷     | **Terminator (Oval)**            | Start ya End batata hai                |
| 🔲     | **Process (Rectangle)**          | Koi operation ya calculation           |
| 🔺     | **Decision (Diamond)**           | Condition check karne ke liye (Yes/No) |
| 🔽     | **Input/Output (Parallelogram)** | Input lena ya Output dena              |
| ➡️     | **Arrow**                        | Flow of logic ya control               |

---

### 📌 Real-life Example:

ATM process mein:

* 🔷 Start
* 🔽 Card input
* 🔺 PIN check (correct ya nahi?)
* 🔲 Amount process
* 🔽 Cash output
* 🔷 End

---

### 🧠 Summary in English:

Flowchart symbols are standard shapes used to visually represent the logic or flow of a program, helping in better understanding and planning.

---

## ✅ **10. Basic Algorithm Types**

---

### ❓ *Q: What are Sequential, Decision-based & Iterative Processing?*

---

### 📘 Hinglish Explanation (Detail mein):

### 🔹 **Sequential Processing:**

Instructions step-by-step chalti hai — no condition, no loop.

🧠 *Example:* 2 numbers add karna:

```python
a = 5
b = 10
sum = a + b
```

---

### 🔹 **Decision-Based Processing (Conditional):**

Code condition ke basis pe alag-alag direction leta hai (if-else).

🧠 *Example:* Positive ya Negative check:

```python
if number > 0:
    print("Positive")
else:
    print("Negative")
```

---

### 🔹 **Iterative Processing (Loops):**

Same set of instructions bar-bar repeat hote hain (loop).

🧠 *Example:* 1 se 5 tak numbers print karna:

```python
for i in range(1, 6):
    print(i)
```

---

### 🧠 Summary in English:

* **Sequential:** Line-by-line execution
* **Decision-based:** Logic branches (if-else)
* **Iterative:** Repeats using loops (for, while)


## ✅ **11. Common Algorithm Examples**


## ✅ **Example 1: Reversing Digits of an Integer**

### 🔢 Code:

```python
num = 1234
reverse = 0
while num != 0:
    reverse = reverse * 10 + (num % 10)
    num = num // 10
print(reverse)
```

### 📘 Line-by-Line Hinglish Explanation:

```python
num = 1234
```

➡️ Humne ek number `1234` liya jiska digits reverse karna hai.

```python
reverse = 0
```

➡️ Ek variable banaya `reverse` — initially `0`, yahi pe hum reverse number banayenge step by step.

```python
while num != 0:
```

➡️ Jab tak `num` zero nahi hota, tab tak loop chalega.
Matlab har iteration mein hum ek digit uthake reverse mein daalte rahenge.

```python
    reverse = reverse * 10 + (num % 10)
```

➡️ Ye **core logic** hai:

* `num % 10` last digit nikalta hai (e.g., 1234 % 10 = 4)
* `reverse * 10` se reverse ke existing digits left shift ho jaate hain
* Fir uske aage new digit add hoti hai

🔁 1st Iteration:

* `reverse = 0 * 10 + 4 = 4`

🔁 2nd Iteration:

* `reverse = 4 * 10 + 3 = 43`

🔁 3rd Iteration:

* `reverse = 43 * 10 + 2 = 432`

🔁 4th Iteration:

* `reverse = 432 * 10 + 1 = 4321`

```python
    num = num // 10
```

➡️ Ye line original number ka **last digit hata rahi hai**, integer division se.
E.g., 1234 → 123 → 12 → 1 → 0

```python
print(reverse)
```

➡️ Final reversed number print kar diya — jo `4321` hai.

---

## ✅ **Example 2: Check if a Number is Prime**

### 🔢 Code:

```python
num = 7
is_prime = True
for i in range(2, int(num ** 0.5) + 1):
    if num % i == 0:
        is_prime = False
        break
print("Prime" if is_prime else "Not Prime")
```

### 📘 Line-by-Line Hinglish Explanation:

```python
num = 7
```

➡️ Number `7` ko check karna hai ki prime hai ya nahi.

```python
is_prime = True
```

➡️ Hum assume karte hain ki number prime hai — agar koi factor mila toh change karenge.

```python
for i in range(2, int(num ** 0.5) + 1):
```

➡️ Loop 2 se start hota hai aur square root tak chalta hai.
Kyu? Kyuki agar koi factor ho toh wo √num ke andar mil jaata hai.

E.g., √7 ≈ 2.64 → `range(2, 3)` ➡ Sirf 2 check hoga.

```python
    if num % i == 0:
```

➡️ Agar number kisi `i` se divide ho gaya (remainder 0) → toh wo prime nahi hai.

```python
        is_prime = False
        break
```

➡️ Jaise hi factor mila, `is_prime` ko `False` banake loop tod diya.

```python
print("Prime" if is_prime else "Not Prime")
```

➡️ Last mein result print kar diya:

* Agar `is_prime` True hai → "Prime"
* Nahi toh → "Not Prime"

---

## ✅ **Example 3: Factorial Computation**

### 🔢 Code:

```python
n = 5
fact = 1
for i in range(1, n + 1):
    fact *= i
print(fact)
```

### 📘 Line-by-Line Hinglish Explanation:

```python
n = 5
```

➡️ Hum factorial `5!` calculate karne wale hain.

```python
fact = 1
```

➡️ Ek variable `fact` liya jisme hum final result store karenge.
Initial value 1 isliye di kyuki factorial mein multiply hota hai.

```python
for i in range(1, n + 1):
```

➡️ Loop chal raha hai `1` se `n` tak (inclusive) — yani `1 se 5 tak`.

```python
    fact *= i
```

➡️ Har step mein `fact` ko `i` se multiply kar rahe hain.
Same as: `fact = fact * i`

Steps:

* 1 × 1 = 1
* 1 × 2 = 2
* 2 × 3 = 6
* 6 × 4 = 24
* 24 × 5 = 120

```python
print(fact)
```

➡️ Final answer print: `5! = 120`

---

## ✅ **Example 4: Swap Two Variables**

### 🔢 Code:

```python
a = 5
b = 10
temp = a
a = b
b = temp
print(a, b)
```

### 📘 Line-by-Line Hinglish Explanation:

```python
a = 5
b = 10
```

➡️ Dono variables declare kiye jinka value swap karna hai.

```python
temp = a
```

➡️ `a` ka value temporarily store kar liya taaki overwrite na ho jaye.

```python
a = b
```

➡️ `a` ke andar `b` ka value daal diya — ab `a = 10`

```python
b = temp
```

➡️ `b` ke andar wo temp wala original `a` ka value daal diya — `b = 5`

```python
print(a, b)
```

➡️ Output: `10 5` — values successfully swapped.

---

## ✅ **5. GCD (Greatest Common Divisor)**

### 🔢 Code:

```python
a = 36
b = 60
while b != 0:
    a, b = b, a % b
print(a)
```

### 📘 Hinglish Line-by-Line Explanation:

```python
a = 36
b = 60
```

➡️ Dono numbers le liye jinka GCD find karna hai.

```python
while b != 0:
```

➡️ Jab tak `b` zero nahi ho jaata, loop chalta rahega.
Ye **Euclidean algorithm** hai.

```python
    a, b = b, a % b
```

➡️ Yahan hum `a` ko `b` bana rahe hain, aur `b` ko `a % b` (modulus) —
Matlab `b` ko replace kar rahe hain remainder se.

Steps:

* a=36, b=60 → a=60, b=36
* a=60, b=36 → a=36, b=24
* a=36, b=24 → a=24, b=12
* a=24, b=12 → a=12, b=0 (loop ends)

```python
print(a)
```

➡️ Jab `b = 0`, tab `a` ke paas GCD hota hai — here `12`

---

## ✅ **6. Fibonacci Sequence**

### 🔢 Code:

```python
n = 7
a, b = 0, 1
for _ in range(n):
    print(a, end=' ')
    a, b = b, a + b
```

### 📘 Hinglish Line-by-Line Explanation:

```python
n = 7
```

➡️ Pehle 7 numbers chahiye Fibonacci sequence ke.

```python
a, b = 0, 1
```

➡️ Initial 2 terms define kar diye — 0 aur 1.

```python
for _ in range(n):
```

➡️ Loop `n` times chalega — `_` ka matlab hai index ki zarurat nahi.

```python
    print(a, end=' ')
```

➡️ Pehla number print karte ja rahe hain har iteration mein.

```python
    a, b = b, a + b
```

➡️ Yaha magic ho raha hai — agla number calculate ho raha hai:

* `a` ban jaata hai `b`,
* `b` ban jaata hai `a + b`

Steps:

* 0 1 → 1
* 1 1 → 2
* 1 2 → 3
* 2 3 → 5
* 3 5 → 8
  \=> Output: `0 1 1 2 3 5 8`

---

## ✅ **7. sin(x) using Series Expansion**

### 🔢 Code:

```python
import math
x = math.radians(30)
terms = 5
sinx = 0
sign = 1
for i in range(terms):
    term = (x ** (2 * i + 1)) / math.factorial(2 * i + 1)
    sinx += sign * term
    sign *= -1
print(sinx)
```

### 📘 Hinglish Line-by-Line Explanation:

```python
import math
```

➡️ `math` module import kiya — factorial aur radians use karne ke liye.

```python
x = math.radians(30)
```

➡️ Angle 30° ko **radians** mein convert kiya, kyunki math functions radians mein kaam karte hain.

```python
terms = 5
```

➡️ Series mein kitne terms chahiye — higher = more accurate.

```python
sinx = 0
```

➡️ Initial result 0 rakha — isme values add/subtract hoti rahengi.

```python
sign = 1
```

➡️ Sign control karta hai: + - + - ... alternate karne ke liye.

```python
for i in range(terms):
```

➡️ Loop 5 baar chalega, har baar ek term compute karega.

```python
    term = (x ** (2 * i + 1)) / math.factorial(2 * i + 1)
```

➡️ sin(x) ka Taylor term:

* x¹/1! - x³/3! + x⁵/5! ...
* Power: `2*i + 1`
* Denominator: factorial of that power

```python
    sinx += sign * term
```

➡️ Alternating sign ke saath result mein add/subtract ho raha hai.

```python
    sign *= -1
```

➡️ Sign ko alternate karne ke liye -1 se multiply kar rahe hain.

```python
print(sinx)
```

➡️ Final approximated `sin(30°)` print ho raha hai — \~0.5 ke aaspaas.

---

## ✅ **8. Reverse Elements of an Array**

### 🔢 Code:

```python
arr = [1, 2, 3, 4, 5]
arr.reverse()
print(arr)
```

### 📘 Hinglish Line-by-Line Explanation:

```python
arr = [1, 2, 3, 4, 5]
```

➡️ Ek list le li — jisme elements ko ulta karna hai.

```python
arr.reverse()
```

➡️ Built-in `reverse()` method se list ke elements ko **in-place** reverse kar diya.

```python
print(arr)
```

➡️ Final reversed list print ho gayi: `[5, 4, 3, 2, 1]`

---

## ✅ **9. Find Largest Number in an Array**

### 🔢 Code:

```python
arr = [4, 9, 1, 17, 2]
largest = arr[0]
for num in arr:
    if num > largest:
        largest = num
print(largest)
```

### 📘 Hinglish Line-by-Line Explanation:

```python
arr = [4, 9, 1, 17, 2]
```

➡️ Array diya gaya — humein sabse bada number find karna hai.

```python
largest = arr[0]
```

➡️ Starting point: pehle element ko maan lete hain "largest".

```python
for num in arr:
```

➡️ Har element ko loop mein check karte hain.

```python
    if num > largest:
        largest = num
```

➡️ Agar koi `num` current `largest` se bada ho, toh `largest` update kar do.

```python
print(largest)
```

➡️ Final result print — yaha 17

---

## ✅ **10. Print Elements of Upper Triangular Matrix**

### 🔢 Code:

```python
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
n = len(matrix)
for i in range(n):
    for j in range(n):
        if i <= j:
            print(matrix[i][j], end=' ')
        else:
            print(" ", end=' ')
    print()
```

### 📘 Hinglish Line-by-Line Explanation:

```python
matrix = [...]
```

➡️ 3x3 matrix define kiya.

```python
n = len(matrix)
```

➡️ Size of matrix store kiya (3).

```python
for i in range(n):
```

➡️ Outer loop: row ke liye.

```python
    for j in range(n):
```

➡️ Inner loop: column ke liye.

```python
        if i <= j:
            print(matrix[i][j], end=' ')
```

➡️ Agar row index <= column index ho, tabhi element print karo.
Ye condition upper triangle ke liye hoti hai (diagonal aur upar wale).

```python
        else:
            print(" ", end=' ')
```

➡️ Niche ke elements ki jagah space print karo.

```python
    print()
```

➡️ Ek row complete hone ke baad nayi line mein jao.

**Output:**

```
1 2 3 
  5 6 
    9 
```

---
