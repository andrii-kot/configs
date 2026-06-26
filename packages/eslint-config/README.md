# @andrii-kot/eslint-config

An opinionated ESLint configuration built on top of `eslint-config-metarhia` and customized for personal and project-specific needs by **Andrii Kotsiuba**.

---

## ✨ Features

- Based on `eslint-config-metarhia`
- Modern ESLint Flat Config (v9+)
- Consistent and maintainable code style
- Additional custom rules and overrides
- Optimized for readability and maintainability
- Ready for Node.js >= 20

---

## Requirements

- Node.js >= 20
- ESLint >= 9

---

## 📦 Installation

Install ESLint and the config:

```bash
npm install -D eslint @andrii-kot/eslint-config
```

---

## ⚙️ Usage

Create `eslint.config.js`:

```js
export { default } from '@andrii-kot/eslint-config';
```

Or extend the config:

```js
import config from '@andrii-kot/eslint-config';

export default [...config];
```

---

## 🚀 CLI Commands

### Lint files

```bash
npx eslint .
```

### Fix problems automatically

```bash
npx eslint . --fix
```

---

## 🧪 Scripts (optional)

Add scripts to your `package.json`:

```json
{
  "scripts": {
    "lint": "eslint .",
    "fix": "eslint . --fix"
  }
}
```

Then run:

```bash
npm run lint
npm run fix
```

---

## 💡 Philosophy

This config follows a simple idea:

> Code style should be consistent, predictable, and automated.

The configuration is based on `eslint-config-metarhia` with additional customizations to enforce maintainable and readable code across projects.

---

> Note: This config uses ESM and ESLint Flat Config. Use `import` / `export` syntax.

## 📄 License

MIT © Andrii Kotsiuba
