# seven-segment-clock

A real-time digital clock written in C that displays the current time in a seven-segment ASCII art style.
The clock updates every second and includes blinking colons (`:`) to mimic real digital clocks.

---

## ✨ Features

* Displays current time in **HH:MM:SS** format
* Seven-segment ASCII art rendering
* **Blinking colon separators** like real digital clocks
* Works on Linux/macOS (`clear`).
  
---

## 📸 Example Output

```
      _            _            _
   |  _|   .  |_|  _|  .  |_|  | |
   | |_    .    |  _|  .    |  |_|
```

Colons (`.`) blink every second.

---

## 🔧 How to Build and Run

```bash
gcc clock.c -o clock
./clock
```
---

## 📂 Project Structure

```
clock.c    # main source code
README.md  # project documentation
```

---

## 📝 License

MIT License – feel free to use, modify, and share.
