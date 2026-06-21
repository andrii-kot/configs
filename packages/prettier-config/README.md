# @andrii-kot/prettier-config

An opinionated Prettier configuration customized for personal and project-specific needs by **Andrii Kotsiuba**.

---

## ✨ Features

- Consistent code formatting across all projects
- Opinionated style (no debates about formatting)
- Works out of the box with Prettier v3+
- Optimized for readability and maintainability
- Ready for Node.js >= 18

---

## Requirements

- Node.js >= 18
- Prettier >= 3

## 📦 Installation

Install Prettier and the config:

```bash
npm install -D prettier git+https://github.com/andrii-kot/prettier-config.git
```

or

```bash
npm install -D github:andrii-kot/prettier-config
```

---

## ⚙️ Usage

Create a `prettier.config.mjs` file in your project:

```js
export { default } from "@andrii-kot/prettier-config";
```

---

## 🧪 Scripts (optional)

Add scripts to your `package.json`:

```json
{
  "scripts": {
    "format": "prettier . --write",
    "check": "prettier . --check"
  }
}
```

---

## 💡 Philosophy

This config follows a simple idea:

> Formatting should be automatic and not discussed.

All stylistic decisions are handled by Prettier, so you can focus on writing code instead of formatting it.

---

## 📄 License

MIT © Andrii Kotsiuba
