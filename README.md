# 🚀 Tailwind CSS v4 Setup Guide

A complete step-by-step guide to install, connect, and use **Tailwind CSS v4** using the official Tailwind CLI.

---

## 📋 Prerequisites

Before getting started, make sure you have:

* ✅ Node.js installed
* ✅ npm installed
* ✅ VS Code (Recommended)

Check your installed versions:

```bash
node -v
npm -v
```

---

# 📦 Step 1: Install Tailwind CSS v4

Install Tailwind CSS and the official CLI package:

> 📌 This is the command that adds Tailwind CSS to your project.

```bash
npm install tailwindcss @tailwindcss/cli
```

---

# 🎨 Step 2: Create the Input CSS File

Create a file named:

```text
input.css
```

Inside the file, add:

```css
@import "tailwindcss";
```

### What does this do?

This imports all Tailwind utilities, components, and core styles into your project.

---

# ⚙️ Step 3: Generate the Output CSS File

Compile Tailwind CSS into a usable CSS file:

```bash
npx @tailwindcss/cli -i ./input.css -o ./output.css
```

### Understanding the command

| Option | Description     |
| ------ | --------------- |
| `-i`   | Input CSS file  |
| `-o`   | Output CSS file |

This command:

📥 Reads from:

```text
input.css
```

📤 Generates:

```text
output.css
```

---

# 🔄 Step 4: Enable Watch Mode (Recommended)

Automatically rebuild CSS whenever you save changes.

```bash
npx @tailwindcss/cli -i ./input.css -o ./output.css --watch
```

### Why use Watch Mode?

✅ No need to run the build command repeatedly

✅ CSS updates automatically

✅ Faster development workflow

Keep this terminal running while developing.

---

# 🔗 Step 5: Connect Tailwind CSS to HTML

Link the generated CSS file inside your HTML document.

```html
<link rel="stylesheet" href="./output.css">
```

Example:

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="./output.css">
</head>
<body>

  <h1 class="text-4xl font-bold text-cyan-500">
    Hello Tailwind CSS 🚀
  </h1>

</body>
</html>
```

---

# 🧪 Step 6: Test the Installation

Add the following code:

```html
<h1 class="text-4xl font-bold text-cyan-500">
  Tailwind is Working! 🚀
</h1>
```

### Expected Result

✅ Large text

✅ Cyan color

✅ Tailwind classes applied

If everything looks correct, Tailwind is connected successfully.

---

# 📁 Recommended Folder Structure

```text
project/
│
├── index.html
├── input.css
├── output.css
├── package.json
├── package-lock.json
│
└── assets/
    ├── images/
    └── icons/
```

---

# 🛠 Development Workflow

### 1️⃣ Install Tailwind

```bash
npm install tailwindcss @tailwindcss/cli
```

### 2️⃣ Create Input File

```css
@import "tailwindcss";
```

### 3️⃣ Start Watch Mode

```bash
npx @tailwindcss/cli -i ./input.css -o ./output.css --watch
```

### 4️⃣ Connect CSS

```html
<link rel="stylesheet" href="./output.css">
```

### 5️⃣ Start Building

Use Tailwind utility classes directly in your HTML.

---

# ⚡ Useful Commands

## 📦 Install Tailwind CSS

```bash
npm install tailwindcss @tailwindcss/cli
```

## 🏗 Build CSS Once

```bash
npx @tailwindcss/cli -i ./input.css -o ./output.css
```

## 👀 Watch Mode

```bash
npx @tailwindcss/cli -i ./input.css -o ./output.css --watch
```

---

# ✅ Setup Checklist

* [x] Node.js Installed
* [x] npm Installed
* [x] Tailwind CSS Installed
* [x] input.css Created
* [x] @import "tailwindcss" Added
* [x] output.css Generated
* [x] HTML Connected to output.css
* [x] Watch Mode Running
* [x] Tailwind Classes Working

---

## 🎉 Congratulations!

Your Tailwind CSS v4 environment is now fully configured and ready for development.

Build fast, create beautiful interfaces, and enjoy the power of utility-first CSS. 🚀✨

---

# 👨‍💻 Author

**Monty Yadav**

- 💻 Web Design & Development
- 🎨 Canva • AI • Creativity
- 🚀 Building in Public
- 🎬 Content • Branding • Editing

Helping small businesses build their online presence through design, websites, content, and AI.

---

⭐ If you found this repository helpful, consider giving it a star.

Made with ❤️ by Monty Yadav
