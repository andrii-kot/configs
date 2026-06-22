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

---

## 📦 Installation

Install Prettier and the config:

```bash
npm install -D prettier @andrii-kot/prettier-config
```

---

## ⚙️ Usage

Add the config to your `package.json`:

```json
{
  "prettier": "@andrii-kot/prettier-config"
}
```

Or using `prettier.config.js`:

```js
export { default } from "@andrii-kot/prettier-config";
```

## 🚀 Commands

### Check formatting

```bash
npx prettier . --check
```

### Format files

```bash
npx prettier . --write
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

> Note: This config uses ESM. Use `import` / `export` syntax.

## 📄 License

MIT © Andrii Kotsiuba
