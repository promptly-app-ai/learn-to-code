- **1.** 📘 [Welcome & How to Use This Guide](README.md)
- **2.** 🚀 [Your First Hour (Do This First)](part2.md)
- **3.** 🧭 [Quick Orientation: How Code Works](part3.md)
- **YOU ARE HERE:** ➡️ **4. 🔍 Curiosity Modules (Choose Your Path)**
- **5.** 🧩 [Core Coding Concepts](part5.md)
- **6.** 🛠️ [Your Beginner Toolkit](part6.md)
- **7.** 🤖 [Learning With AI](part7.md)
- **8.** 🧠 [How AI Works](part8.md)
- **9.** 🌱 [Next Steps](part9.md)

---

# **PART 4 — 🔍 Curiosity Modules (Choose Your Path)**

*Short, visual, skimmable modules designed to spark interest — explore in any order.*

---

Each module includes:

* a friendly 2–4 sentence explanation
* a tiny optional code snippet (only if helpful)
* **curated visual explainers** (YouTube, TikTok, PythonTutor, etc.)
* optional micro-exercises

These are not lessons — they’re **jumping-off points** to help your brain connect the dots in whatever order feels natural.

---

# 🌐 **MODULE A — “What’s the difference between a website and an app?”**

At a high level:

* A **website** runs inside a browser (Chrome, Safari, Firefox).
* An **app** is installed on your phone or computer and runs directly on the device.
* Both follow similar ideas: code → logic → output → interaction.

A simple picture:

```
[ Browser ] → opens a website (JavaScript runs here)
[ Phone  ] → opens an app (Swift/Kotlin runs here)
```

### **Great visual explainers**

* Watch this quick video on [how websites work (YouTube)](https://youtube.com/)
* A simple animation showing [client vs server (YouTube)](https://youtube.com/)
* TikTok explainer from [tt/thecodercoder](https://tiktok.com/)

### **Try this (optional)**

On PlayCode, paste this to simulate a “button click”:

```javascript
console.log("Imagine this is a button: [Click]");
```

Later you’ll learn how real buttons work, but this is your first step toward interaction.

---

# 🧠 **MODULE B — “Why do programmers use different languages?”**

Programming languages are like different tools:

* JavaScript → websites
* Python → data, automation
* Swift → iPhone apps
* Kotlin → Android apps
* SQL → databases
* C++ → performance-heavy tasks

Think of it like cooking utensils: a whisk isn’t better than a spatula — it just solves a different problem.

### **Great visual explainers**

* Simple breakdown of [programming languages explained (YouTube)](https://youtube.com/)
* What languages do what? [Visual guide (YouTube)](https://youtube.com/)
* Quick TikTok overview from [tt/harvardcs50](https://tiktok.com/)

### **Optional code comparison**

**JavaScript:**

```javascript
console.log("Hello from JavaScript");
```

**Python:**

```python
print("Hello from Python")
```

Same concept, two flavors.

---

# 🔘 **MODULE C — “What happens when you click a button?”**

When you click a button on a webpage:

1. The browser detects the click
2. JavaScript reacts to the click
3. Something changes — text, color, movement

Here’s a tiny simulation in PlayCode:

```html
<button onclick="console.log('You clicked the button!')">Click me</button>
```

(PlayCode supports HTML + JS together.)

### **Great visual explainers**

* How browser events work [explainer (YouTube)](https://youtube.com/)
* DOM (the structure of a webpage) [visual intro (YouTube)](https://youtube.com/)
* TikTok example from [tt/frontendengineer](https://tiktok.com/)

### **Try this**

Change the message inside the quotes and click again.

---

# 💾 **MODULE D — “How does a computer *remember* things?” (Variables)**

A variable is a labeled box that holds a value.

```
[ name ] → "Jamie"
[ age  ] → 22
```

In JavaScript:

```javascript
let name = "Jamie";
console.log(name);
```

In Python:

```python
name = "Jamie"
print(name)
```

### **Great visual explainers**

* Visual beginner guide to [variables (YouTube)](https://youtube.com/)
* Memory explained super simply [CS Dojo (YouTube)](https://youtube.com/)
* TikTok from [tt/codingwithmitch](https://tiktok.com/)

### **Try this**

Change the value, run again.
Then remove the quotes — see what happens.

---

# 🔁 **MODULE E — “How does a loop work?”**

Loops repeat instructions until something stops them.

Real life analogy:

> “Keep watering the plants until every one has water.”

JavaScript:

```javascript
for (let i = 1; i <= 3; i++) {
  console.log("Loop number:", i);
}
```

Python:

```python
for i in range(1, 4):
    print("Loop number:", i)
```

### **Great visual explainers**

* Watch this animation on [how loops work (YouTube)](https://youtube.com/)
* See each loop iteration visually in [PythonTutor](https://pythontutor.com/javascript.html)
* A TikTok snippet explaining loops: [tt/cs_dojo](https://tiktok.com/)

### **Try this**

Change the number `3` to `10`.
Then try `i += 2` (JS) or `range(1, 10, 2)` (Python).

---

# 💥 **MODULE F — “Why do programs break?” (Understanding Errors)**

Errors aren’t bad — they’re clues.

Common beginner issues:

* Missing quotes
* Missing parentheses
* Misspelling a variable
* Forgetting a bracket

Example error:

```javascript
console.log("Missing quote);
```

### **Great explainers**

* “Why your code breaks” [beginner explainer (YouTube)](https://youtube.com/)
* Debugging basics from [CS Dojo (YouTube)](https://youtube.com/)
* Real quick examples from [tt/thecodercoder](https://tiktok.com/)

### **Try this**

Break something on purpose → run → read the error → fix it.
This builds real coding intuition faster than anything else.

---

# 👀 **MODULE G — “How can I *see* what my code is doing?”**

Sometimes it’s hard to visualize what’s happening inside the computer. Good news: there’s a tool for that.

➡️ Visualize any code with **PythonTutor**:
[https://pythontutor.com/javascript.html](https://pythontutor.com/javascript.html)

Paste this:

```javascript
let a = 5;
let b = a + 2;
console.log(b);
```

Then click **Visualize Execution**.

You'll see the computer process your program line by line.

### **Great explainers**

* Full tour of PythonTutor [visual intro (YouTube)](https://youtube.com/)
* Step-through example from [tt/computer_science_basics](https://tiktok.com/)

### **Try this**

Change the number `5` to `"hello"` — observe the difference.

---

# 🌍 **MODULE H — “What happens when a webpage loads?”**

When you type a URL and press Enter:

```
[ Browser ] → sends request → [ Server ]
[ Server ] → sends back HTML/CSS/JS → [ Browser ]
[ Browser ] → shows you the webpage
```

It’s just a back-and-forth conversation.

### **Great visual explainers**

* Basics of the Internet [animated (YouTube)](https://youtube.com/)
* Client vs server [simple animation (YouTube)](https://youtube.com/)
* TikTok from [tt/techwithtim](https://tiktok.com/)

### **Try this**

Open your browser’s “View Source” on any website.
You’re looking at the raw HTML the server sent.

---

# 🎨 **MODULE I — “How do drawings, animations, or games appear on a screen?”**

The **Canvas** in JavaScript lets you draw shapes and images.

Try this on PlayCode:

```html
<canvas id="c" width="200" height="200"></canvas>
<script>
  const canvas = document.getElementById("c");
  const ctx = canvas.getContext("2d");
  ctx.fillStyle = "red";
  ctx.fillRect(20, 20, 160, 160);
</script>
```

You just drew something with code.

### **Great visual explainers**

* What is the Canvas? [visual intro (YouTube)](https://youtube.com/)
* JavaScript drawing basics [animated (YouTube)](https://youtube.com/)
* TikTok from [tt/webdevcody](https://tiktok.com/)

### **Try this**

Change `"red"` to `"blue"` or `"green"`.

---

# 🕹️ **MODULE J — “What is a puzzle site? Why do people use them?”**

Puzzle sites help you practice real problem-solving — not syntax memorization.

Beginner-safe visual puzzle sites:

* **CheckIO (Python/JS)**: [https://checkio.org](https://checkio.org)
* **Exercism (mentors included)**: [https://exercism.org](https://exercism.org)
* **CodingBat (very beginner-friendly)**: [https://codingbat.com](https://codingbat.com)

### **Try this**

Pick a single CheckIO puzzle and attempt the simplest version.
If stuck, ask AI:

> “Can you give me a hint, not the answer?”

---

## 👉👉 **NEXT:** **5.** 🧩 [Core Coding Concepts](part5.md) 👈👈

### Contents

- **1.** 📘 [Welcome & How to Use This Guide](README.md)
- **2.** 🚀 [Your First Hour (Do This First)](part2.md)
- **3.** 🧭 [Quick Orientation: How Code Works](part3.md)
- **YOU ARE HERE:** ➡️ **4. 🔍 Curiosity Modules (Choose Your Path)**
- **5.** 🧩 [Core Coding Concepts](part5.md)
- **6.** 🛠️ [Your Beginner Toolkit](part6.md)
- **7.** 🤖 [Learning With AI](part7.md)
- **8.** 🧠 [How AI Works](part8.md)
- **9.** 🌱 [Next Steps](part9.md)
