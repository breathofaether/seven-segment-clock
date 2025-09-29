# seven-segment-clock
# Seven-Segment Digital Clock in C

A simple real-time digital clock written in C that displays the current time in a seven-segment ASCII art style.
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

## 🚀 Possible Extensions

* Add command-line flag for **12h / 24h** mode
* Display **HH:MM** only (without seconds)
* Add color output (using ANSI escape codes)

---

## 📝 License

MIT License – feel free to use, modify, and share.
