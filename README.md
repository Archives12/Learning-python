# 🐍 Python Learning Journey

> *Master Python, one concept at a time!*

Welcome to my **Python Learning Repository** – a carefully curated collection of notebooks that document my journey from Python basics to advanced concepts. Each notebook is a stepping stone in mastering this versatile language!

---

## 🌟 What You'll Find Here

| Concept | Description | Notebook |
|--------|-------------|----------|
| 🧱 Basics | Python syntax, variables, data types | `basic.ipynb` |
| ⚖️ Conditionals | If/elif/else, logical decision making | `conditionals.ipynb` |
| 🔧 Operators | Arithmetic, comparison, logical ops | `operator.ipynb` |
| 🔄 TypeCasting | Converting between data types | `typecasting.ipynb` |
| 🌀 Mutability | Mutable vs immutable objects | `mutability.ipynb` |
| 🔁 Loops | For/while loops, loop control | `loops.ipynb` |
| 📁 File Handling | Read/write txt, csv, json files | `file_handling.ipynb` |
| 🐛 Debugging | Debuggers, logging, tracing | `debugging.ipynb` |
| ⚡ Functions | Defining, parameters, returns | `functions.ipynb` |
| 🏗️ OOP | Classes, objects, inheritance | `oop.ipynb` |
| 📦 Modules | Importing, creating packages | `modules.ipynb` |
| 🛡️ Error Handling | Try/except, custom exceptions | `error_handling.ipynb` |

---

## 📂 Repository Map

```text
Learning-python/
├── Foundation/
│   ├── basic.ipynb
│   ├── operator.ipynb
│   └── typecasting.ipynb
│
├── Control-Flow/
│   ├── conditionals.ipynb
│   └── loops.ipynb
│
├── Core-Concepts/
│   ├── mutability.ipynb
│   └── functions.ipynb
│
├── Real-World-Skills/
│   ├── file_handling.ipynb
│   ├── debugging.ipynb
│   └── error_handling.ipynb
│
└── Advanced-Python/
    ├── oop.ipynb
    └── modules.ipynb
```
---

## 🚀 Quick Start Guide

### Clone & Explore

```bash
# Step into the Python world
git clone https://github.com/Archives12/Learning-python.git
cd Learning-python

# Set up your environment
pip install -r requirements.txt

# Launch your learning adventure!
jupyter notebook
```

---

## 🎯 Learning Strategy

- Start Simple → Begin with `basic.ipynb` to build your foundation  
- Practice Daily → Run code, modify examples, break things!  
- Build Projects → Apply concepts to mini-projects  
- Debug Fearlessly → Use `debugging.ipynb` to learn from mistakes  

---

## 💡 Pro Tips for Learners

> *"The code you write today is better than the perfect code you never write."*

- 🎮 Experiment: Change values, break code, then fix it!  
- 📝 Comment: Add your own explanations as you learn  
- 🔄 Revisit: Old notebooks with new knowledge = deeper understanding  
- 🧩 Combine: Mix concepts from different notebooks  

---

## 🧪 From `debugging.ipynb` – A Neat Debugging Decorator

```python
import time

def debug_time(func):
    """Decorator to measure function execution time"""
    def wrapper(*args, **kwargs):
        start = time.time()
        result = func(*args, **kwargs)
        end = time.time()
        print(f"⏱️  {func.__name__} took {end-start:.4f} seconds")
        return result
    return wrapper

@debug_time
def process_data(data):
    # Your complex processing here
    return sorted(data)
```

---

## 👩‍💻 About the Author

**Priya Mehta**  
Python Enthusiast & Continuous Learner  
📧 Learning in public, one commit at a time!

---

## ✨ Star This Repository

If you find this helpful, give it a ⭐!  
It motivates me to keep adding more content.

---

## 📬 Stay Updated

Watch this repo to get notified about new notebooks and updates!

---

> *"Python is not just a language; it's a playground for the curious mind."*

**Last Updated:** February 2024  
**Made with ❤️ and ☕**
