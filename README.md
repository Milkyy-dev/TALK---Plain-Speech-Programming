# TALK---Plain-Speech-Programming

# ✨ TALK Language

**TALK** is a beginner-friendly, human-readable programming language built with Python. Designed for simplicity and clarity, it allows users to write understandable code in everyday language.

---

## 🚀 Getting Started

### ▶️ Running a `.talk` File

To run a `.talk` file:

```bash
python talk.py myprogram.talk
```

Make sure `talk.py` and your `.talk` file are in the same directory.

---

## 🧠 Core Concepts

TALK uses commands that mimic natural language. It supports:

- Output and interaction (`say`, `input`)
- Variables and arithmetic (`set`, `add`, `sub`, etc.)
- Lists and logic (`list`, `append`, `if`)
- Control flow (`repeat`, `wait`, `exit`)
- Utility operations (`random`, `clear`)

---

## 📚 Commands Reference

### 🗣️ `say`

Outputs text to the screen.

```talk
say "Hello, world!"
say "You are " + name
```

---

### 🧾 `set`

Assigns a value to a variable.

```talk
set age = 25
set name = "Alice"
```

---

### 🧮 Math Operations

These operate on numeric variables.

```talk
add score 10       # score = score + 10
sub lives 1        # lives = lives - 1
mul total 5        # total = total * 5
div distance 2     # distance = distance / 2
```

---

### ⌨️ `input`

Asks the user for input. Input is stored in a variable.

```talk
input name "What is your name?"
say "Hello, " + name + "!"
```

---

### 🔁 `repeat`

Repeats a block of code.

```talk
repeat 3
    say "This prints 3 times"
```

---

### ⏱️ `wait`

Waits for a given number of seconds.

```talk
wait 2
```

---

### 🎲 `random`

Generates a random number between two bounds and stores it.

```talk
random randNum 1 100
say "Your lucky number is " + randNum
```

---

### 🧼 `clear`

Clears the screen (console).

```talk
clear
```

---

### ❌ `exit`

Exits the interpreter.

```talk
exit
```

---

### 📋 `list`

Creates a list and stores it in a variable.

```talk
list fruits = ["apple", "banana"]
```

### ➕ `append`

Adds an item to the end of a list.

```talk
append fruits "orange"
```

### 📏 `length`

Stores the length of a list in a variable.

```talk
length fruits count
say "You have " + count + " fruits."
```

---

## 🧪 Conditional Logic (Coming Soon or Custom Feature)

You can simulate logic with nested structures or request future support for:

```talk
if score > 100
    say "You win!"
else
    say "Try again!"
```

Currently, full conditional logic parsing inside `.talk` blocks is limited, but it can be emulated via Python backend expansion.

---

## 🧠 Example Program

```talk
say "What is your name?"
input name "Enter your name: "
say "Hello, " + name + "!"

set score = 10
add score 5
say "Your score is " + score

list fruits = ["apple", "banana"]
append fruits "grape"
length fruits total
say "Fruits: " + fruits
say "Total fruits: " + total
```

## 💻 More Commands! Ascii Rendering and a WIP GRE (Graphics Runtime Engine)

## GRE Example
```
clear 0x000000
rect 100 100 200 150 0xFF0000
pixel 150 150 0x00FF00
pixel 160 160 0x0000FF
```
## Ascii Example
```
# Clear the screen (all pixels intensity 0)

clear

# Draw a diagonal line with intensity 9 (brightest)

set_pixel 0 0 9
set_pixel 1 1 8
set_pixel 2 2 7
set_pixel 3 3 6
set_pixel 4 4 5
set_pixel 5 5 4
set_pixel 6 6 3
set_pixel 7 7 2
set_pixel 8 8 1
set_pixel 9 9 0

# Render the current pixel buffer to the console

render
```


---

## 🛠️ Developer Notes

- Built in **Python 3**
- Designed for educational and prototyping use
- Easily extendable with new commands

You can add new commands by editing the `interpret_line()` function in `talk.py`.

---

## 📎 To-Do Ideas

- [ ] Better interpreter
- [ ] More commands (Still working on)
- [ ] Syntax highlighting
- [ ] VSCode Extension
- [ ] Libraries! 
- [ ] Graphics Rendering :D (Kinda done)
---

## 📣 Contributing

Feel free to fork and expand. TALK is a sandbox for exploring how to make coding accessible and human-readable.

#  ==================== TALK Multi-Purpose ====================
#  ==================== Milky-Dev / Milky ===================
#  ==================== UPDATED: 6/20/2025 ==================
#  ============ Free For Personal / Commerical Use ==========
