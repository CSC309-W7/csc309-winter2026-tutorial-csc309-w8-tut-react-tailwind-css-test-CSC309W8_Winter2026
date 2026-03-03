
# CSC309 – Week 8 Code Challenge (React + Tailwind)

## Deadline

**End of this tutorial**

## Start

Get the starter code from **GitHub Classroom** (link on Quercus / QR code).

After accepting the assignment:

1. Clone your repository
2. Open the project folder in VSCode

---

## ⚠️ Important: `node_modules/` is NOT included

Your starter repo does **not** include `node_modules/`.

So after you clone the repo, you **must** install dependencies before running the project:

```bash
cd w8
npm install
```

---

## What’s Already Set Up For You

This starter repo already includes:

* ✅ Vite + React (plain JavaScript)
* ✅ Tailwind CSS v4 configured and ready
* ✅ Easter egg image in `public/`
* ✅ A working dev server setup

You **do not** need to set up Tailwind or Vite.

---

## Project Structure

```
w8/
├── public/
│   └── easter_egg.jpg
├── src/
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── package-lock.json
└── vite.config.js
```

---

## What You Should / Should Not Edit

### ✅ You SHOULD modify

#### `src/App.jsx`

Build the UI here (layout, cards, button, Easter egg logic).

> Most (or all) of your code goes here.

---

### ✅ You MAY look at (but usually don’t need to change)

#### `src/index.css`

Tailwind is loaded here and should already include:

```css
@import "tailwindcss";
```

---

### ❌ You should NOT modify

These are pre-configured starter files and changing them may break your project:

* `src/main.jsx`
* `vite.config.js`
* `index.html`
* `package.json` / `package-lock.json`

Also do **not** commit `node_modules/` (it is intentionally excluded).

---

## Figma Design

The Figma file is located at:

```
/Figma/w8_code_challenge_figma_design.png
```

Follow the design as closely as possible.

---

## Tasks

### Task 1 — Build the Page (React + Tailwind Only)

Create a **one-page website** using:

* ✅ React
* ✅ Tailwind CSS utility classes only
* ❌ No custom CSS files
* ❌ No inline styles like `style={{ ... }}`
* ❌ No external UI libraries (Bootstrap, MUI, etc.)

---

### Task 2 — Easter Egg Feature

When the user clicks the **Button** on your website, the Easter egg should pop up.

The image is already provided at:

```
public/easter_egg.jpg
```

In React, you can display it using:

```jsx
<img src="/easter_egg.jpg" alt="Easter Egg" />
```

The Easter egg must be clearly visible (modal / overlay / popup are all fine).

---

## How to Run (Dev Server)

Inside the project root (`w8/`), run:

### 1) Install dependencies (required once)

```bash
npm install
```

### 2) Start the dev server

```bash
npm run dev
```

Then open the URL shown in your terminal (usually `http://localhost:5173`).

---

## Submission

Push your changes to github before the end of the tutorial.

---

## Marking (In-Person)

Before you leave:

> Show your website to your TA for verification.
