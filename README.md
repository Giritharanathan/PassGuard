# 🔐 PassGuard

A simple password strength checker built with plain HTML, CSS and JavaScript. No libraries, no frameworks — just beginner-friendly web code!

---

## 🌟 Features

- 🎲 **Entropy calculation** — shows how random your password really is (in bits)
- ⏱️ **Crack time estimate** — tells you how long it would take a hacker to crack it
- 🔠 **Charset size** — counts how many possible characters are in your password pool
- ⭐ **Strength score** — gives a proper score out of 5 (not just yes/no checks)
- ✅ **Live checklist** — green/red checks for each password rule
- 👁️ **Show/hide toggle** — see your password while typing
- 💡 **Tips** — tells you exactly what to improve

---

## 📸 Preview

> Dark themed UI with a strength bar, info grid, and checklist — all in one page!

---

## Live Demo
> https://Giritharanathan.github.io/PassGuard/

## 🚀 How to Use

1. Download or clone this repo
2. Open `index.html` in your browser
3. Type a password and click **Analyse Password**
4. That's it! 🎉

```bash
git clone https://github.com/your-username/password-analyser.git
cd password-analyser
# just open index.html in your browser!
```

---

## 📁 Project Structure

```
password-analyser/
│
└── index.html       # everything is in one file!
```

---

## 🧠 How the Scoring Works

The score is out of **5** and is calculated based on:

| Check | Max Points |
|---|---|
| Password length | 30 pts |
| Numbers | 15 pts |
| Uppercase letters | 15 pts |
| Lowercase letters | 10 pts |
| Special characters | 20 pts |

Penalties are applied for:
- 🔁 Repeating the same characters too much
- 🚫 Using a very common password like `123456` or `password`

The entropy is calculated as:

```
entropy = length × log2(charset size)
```

Crack time assumes **10 billion guesses per second** (modern GPU attack).

---

## 🛠️ Built With

- HTML
- CSS
- JavaScript (vanilla, no libraries!)

---

## 👶 Who is this for?

This project is great for:
- Beginners learning web development
- Anyone who wants to understand how password strength works
- A fun little portfolio project!

---

## 📄 License

This project is open source and free to use. Do whatever you want with it! 😄

---

Made with ❤️ and plain JavaScript
