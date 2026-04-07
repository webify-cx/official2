# 🚀 GitHub – Naye Project Ka Complete Guide
> **By TechPeer** | Har naye project ke liye follow karo yeh steps

---

## ✅ Ek Baar Setup (Sirf Pehli Baar)

### 1. Git Install Karo
- Download karo: https://git-scm.com/download/win
- Install karo (default options theek hain)
- Check karo: `git --version`

### 2. Git ko Apni Pehchaan Dو
Terminal / Git Bash mein yeh likho:
```bash
git config --global user.name "Aneel Raza"
git config --global user.email "tumhari-email@gmail.com"
```

### 3. GitHub Pe Google Se Login
- Jao: https://github.com
- **Sign up / Login → Continue with Google**
- Account ban gaya ✅

---

## 🆕 Har Naye Project Ke Liye – Step by Step

### Step 1 – GitHub Pe Naya Repo Banao

1. GitHub pe jao → **"New"** button dabao (green wala)
2. **Repository name** likho → e.g. `Webify`
3. **Private** ya **Public** choose karo
4. ✅ **"Add a README file"** check karo
5. **"Create repository"** dabao

---

### Step 2 – Apne PC Pe Project Folder Banao

```
E:\Webify   ← yahan tumhara project hoga
```

Terminal kholo (Git Bash ya VS Code Terminal) aur likho:
```bash
cd E:\Webify
```

---

### Step 3 – Git Initialize Karo (Folder Ko Git Se Jodo)

```bash
git init
```

> ✅ Iska matlab: "Yeh folder ab Git track karega"

---

### Step 4 – GitHub Repo Ko PC Se Connect Karo

GitHub pe naye repo mein jao → **"Code"** button → HTTPS link copy karo
Phir terminal mein:

```bash
git remote add origin https://github.com/tumhara-username/Webify.git
```

> ✅ Iska matlab: "Mera PC ab is GitHub repo se baat karega"

---

### Step 5 – Pehli Baar Code GitHub Pe Bhejo

```bash
git add .
git commit -m "First commit – project shuru"
git branch -M main
git push -u origin main
```

> ✅ Bas! Tumhara code GitHub pe live hai 🎉

---

## 🔁 Roz Ka Kaam – Code Update Karna

Jab bhi naya code likhو, yeh 3 commands:

```bash
git add .
git commit -m "Jo kiya woh likho – e.g. navbar banaya"
git push
```

> 💡 **Tip:** Commit message meaningful rakho. "Update" mat likho, likho "Login page ka form banaya"

---

## 🧠 Important Commands – Quick Reference

| Command | Kya Karta Hai |
|---|---|
| `git init` | Folder ko Git se connect karo |
| `git status` | Dekho kya kya change hua |
| `git add .` | Sab changes stage karo |
| `git commit -m "msg"` | Changes save karo with message |
| `git push` | GitHub pe bhejo |
| `git pull` | GitHub se latest code lo |
| `git log` | Purani commits dekho |
| `git clone URL` | Kisi repo ko PC pe copy karo |

---

## ⚠️ Common Mistakes – Bachte Rehna

| Galti | Sahi Tarika |
|---|---|
| `git push` bina `git add .` ke | Pehle `add`, phir `commit`, phir `push` |
| Commit message blank chhodi | Hamesha meaningful message likho |
| Wrong folder mein git init | `cd` se pehle sahi folder mein jao |
| `.env` ya secrets push kar diye | `.gitignore` file banao pehle |

---

## 🛡️ .gitignore – Secret Files GitHub Pe Mat Bhejo

Project folder mein `.gitignore` file banao:

```
node_modules/
.env
.DS_Store
*.log
```

> ✅ Yeh files kabhi GitHub pe nahi jayengi

---

## 🔄 Example – "Webify" Project Complete Flow

```bash
# 1. Folder mein jao
cd E:\Webify

# 2. Git shuru karo
git init

# 3. GitHub se connect karo
git remote add origin https://github.com/aneel/Webify.git

# 4. Pehla push
git add .
git commit -m "Webify project start"
git branch -M main
git push -u origin main

# 5. Roz ka kaam
git add .
git commit -m "Home page layout banaya"
git push
```

---

## 📌 Yaad Rakhne Wali Baat

> **GitHub = Tumhara Code Ka Bank**
> - `commit` = Paisa jama karna (locally save)
> - `push` = Bank mein transfer karna (GitHub pe bhejo)
> - `pull` = ATM se nikalna (GitHub se lo)

---

*Made with ❤️ by TechPeer | github.com/techpeer*
