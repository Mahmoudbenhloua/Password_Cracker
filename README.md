# 🔐 Password Cracker (Educational Tool)

This project is a simple **password cracking script** developed for educational and cybersecurity training purposes. It demonstrates the use of **brute-force** and **dictionary attack** methods to test password strength.

---

## 🚀 Features

- Brute-force attack using custom character sets
- Dictionary attack using wordlists
- Easy-to-read CLI output
- Time and attempt tracking

---

## 🧠 Educational Purpose

> ⚠️ **This tool is for ethical and educational use only.**  
> It should **never** be used against systems or data you don't own or have explicit permission to test.

---

## 🛠️ Technologies Used

- Python 3
- `itertools`, `time`, `argparse`

---

## 🧪 Example Usage

```bash
python cracker.py --mode brute --charset abc123 --max-length 4 --target 1a2b
