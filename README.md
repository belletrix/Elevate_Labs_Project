# 🔐 Password Strength Analyzer & Wordlist Generator

This is a simple Python tool that:
- Analyzes the strength of a given password using basic logic.
- Generates a **custom wordlist** from personal inputs like your name, pet name, or birthdate.
- Does **not require any external Python libraries**, so it's perfect for systems like **Kali Linux**.

---

## 📁 File Name:
```bash
password_tool.py
```

---

## 🛠 Features
- ✅ Simple password strength check (Strong / Medium / Weak)
- ✅ Leetspeak variants (e.g., `tommy` → `t0mmy`)
- ✅ Year-based combinations (e.g., `heenal2024`, `20242004`)
- ✅ Wordlist saved as a `.txt` file

---

## 💻 How to Run

### 1. Open Terminal in the file's directory
```bash
cd /path/to/your/file
```

### 2. Run the script
```bash
python3 password_tool.py --password "Heenal@123" --name "Heenal" --date "22June2004" --pet "Tommy"
```

---

## 🧠 Password Strength Logic
- **Strong**: 8+ characters with uppercase, lowercase, digits, and symbols.
- **Medium**: Only length is 8+, but lacks full complexity.
- **Weak**: Too short or too simple.

---

## 📦 Output
- Console displays password strength.
- A wordlist file `simple_wordlist.txt` is saved in the same directory.

---

## 📌 Example Output:
```bash
Password Strength: Strong
Wordlist saved to simple_wordlist.txt with 38 entries.
```

---

## 📂 Example Wordlist Entries:
```
heenal
h33nal
heenal2024
2024heenal
t0mmy
tommy2004
...
```

---

## 📝 Author
- **Heenal Sharma**
- Kali Linux | Python3
