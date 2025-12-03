- **1.** 📘 [Welcome & How to Use This Guide](README.md)
- **2.** 🚀 [Your First Hour (Do This First)](part2.md)
- **3.** 🧭 [Quick Orientation: How Code Works](part3.md)
- **4.** 🔍 [Curiosity Modules (Choose Your Path)](part4.md)
- **YOU ARE HERE:** ➡️ **5. 🧩 Core Coding Concepts**
- **6.** 🛠️ [Your Beginner Toolkit](part6.md)
- **7.** 🤖 [Learning With AI](part7.md)
- **8.** 🧠 [How AI Works](part8.md)
- **9.** 🌱 [Next Steps](part9.md)

---

# **PART 5 — Core Coding Concepts (Short, Friendly Modules)**

*These are the foundations you’ll see in every language. Each module includes: a simple definition, a tiny JS example, a tiny Python example, and a quick try-it-yourself idea.*

---

These modules are intentionally short and clear — **no jargon, no deep theory, no heavy explanations.**
They exist to build familiarity, not mastery.

Explore in any order.

---

# 📦 **MODULE 1 — Variables (“Remembering things”)**

A variable is a container that stores a piece of information.

Think of it as a labeled box:

```
[ username ] → "River"
[ age ]      → 19
```

### **JavaScript**

```javascript
let username = "River";
console.log(username);
```

### **Python**

```python
username = "River"
print(username)
```

### **Try this**

Change the value, run again.
Then store a number and add 2 to it.

---

# 🧮 **MODULE 2 — Data Types (Kinds of values)**

Common types:

* **Text** → `"hello"`
* **Numbers** → `42`
* **True/False** → `true` / `false` (JS), `True` / `False` (Python)
* **Lists/arrays** → `[1, 2, 3]`
* **Dictionaries/objects** → `{name: "Jamie", age: 22}`

### **JavaScript**

```javascript
console.log("hello");
console.log(42);
console.log(true);
```

### **Python**

```python
print("hello")
print(42)
print(True)
```

### **Try this**

Mix types: `console.log("Age:", 30);`.
Then try a list: `[10, 20, 30]`.

---

# 🔁 **MODULE 3 — Loops (Doing something many times)**

*A gentle refresher from Part 4 but with slightly deeper clarity.*

Loops let you repeat actions without rewriting lines.

### **JavaScript**

```javascript
for (let i = 1; i <= 3; i++) {
  console.log("Step:", i);
}
```

### **Python**

```python
for i in range(1, 4):
    print("Step:", i)
```

### **Try this**

Change the limit (`3` → `5`).
Try counting by 2s.

### **Visualize it**

* Visual [step-through using PythonTutor](https://pythontutor.com/javascript.html)

---

# 🔀 **MODULE 4 — Conditionals (“If this, then that”)**

Conditionals let your program make decisions.

### **JavaScript**

```javascript
let score = 80;

if (score > 70) {
  console.log("You passed!");
} else {
  console.log("Try again.");
}
```

### **Python**

```python
score = 80

if score > 70:
    print("You passed!")
else:
    print("Try again.")
```

### **Try this**

Change the number — watch the message change.

### **Visual explainer**

* Beginner explanation of [if/else logic (YouTube)](https://youtube.com/)

---

# 🧩 **MODULE 5 — Functions (“Reusable actions”)**

A function is a tiny machine that does something when you call it.

```
input → function → output
```

### **JavaScript**

```javascript
function greet(name) {
  console.log("Hello, " + name);
}

greet("Sky");
```

### **Python**

```python
def greet(name):
    print("Hello, " + name)

greet("Sky")
```

### **Try this**

Change the name.
Add another parameter, like `age`.

### **Visual explainer**

* Friendly guide to [functions (YouTube)](https://youtube.com/)

---

# 📚 **MODULE 6 — Parameters (“Inputs to functions”)**

A function can accept values (parameters) that change how it behaves.

### **JavaScript**

```javascript
function add(a, b) {
  console.log(a + b);
}

add(3, 5);
```

### **Python**

```python
def add(a, b):
    print(a + b)

add(3, 5)
```

### **Try this**

Try subtracting instead of adding.
Try passing strings instead of numbers.

---

# 📋 **MODULE 7 — Lists / Arrays (“Collections of things”)**

A list/array holds many values in order.

```
[ "apple", "banana", "cherry" ]
```

### **JavaScript**

```javascript
let fruits = ["apple", "banana", "cherry"];
console.log(fruits[1]); // banana
```

### **Python**

```python
fruits = ["apple", "banana", "cherry"]
print(fruits[1])  # banana
```

### **Try this**

Add a fruit.
Change the index number.

### **Visual explainer**

* See lists visually with [PythonTutor](https://pythontutor.com/javascript.html)

---

# 🗂️ **MODULE 8 — Objects / Dictionaries (“Labeled data”)**

Objects/dictionaries store information in key–value pairs.

```
{name: "Ava", age: 14}
```

### **JavaScript**

```javascript
let person = { name: "Ava", age: 14 };
console.log(person.name);
```

### **Python**

```python
person = {"name": "Ava", "age": 14}
print(person["name"])
```

### **Try this**

Add a new field, like `favoriteColor`.

---

# 🧨 **MODULE 9 — Errors & Debugging (Finding and fixing issues)**

Errors are not failures — they’re clues.

Common errors:

* missing quotes
* missing parentheses
* undefined variables
* typos

### **Example (JS)**

```javascript
console.log("Missing quote);
```

### **Try this**

Break your code on purpose.
Run it.
Read the error message.
Fix it.

### **When stuck, ask AI:**

> “Can you explain this error in simple terms and show me what usually causes it?”

---

# 🗺️ **MODULE 10 — Execution Environments (Where code runs)**

Code can run in different places:

```
Browser (JS)
Server  (Node, Python, etc.)
Device  (Swift, Kotlin)
```

For now, the **browser** is your home base.

### **Try this**

Open DevTools → Console (in Chrome) and type:

```javascript
console.log("Hi from the browser console!");
```

You just ran JS directly inside your browser.

---

## 👉👉 **NEXT:** **6.** 🛠️ [Your Beginner Toolkit](part6.md) 👈👈

### Contents

- **1.** 📘 [Welcome & How to Use This Guide](README.md)
- **2.** 🚀 [Your First Hour (Do This First)](part2.md)
- **3.** 🧭 [Quick Orientation: How Code Works](part3.md)
- **4.** 🔍 [Curiosity Modules (Choose Your Path)](part4.md)
- **YOU ARE HERE:** ➡️ **5. 🧩 Core Coding Concepts**
- **6.** 🛠️ [Your Beginner Toolkit](part6.md)
- **7.** 🤖 [Learning With AI](part7.md)
- **8.** 🧠 [How AI Works](part8.md)
- **9.** 🌱 [Next Steps](part9.md)
