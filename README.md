# Tailwind CSS Testing

## Description
A modern project utilizing **Tailwind CSS** with a **Prettier plugin for Tailwind** to ensure well-structured and optimized styling. This project demonstrates the integration of Tailwind CSS into a development workflow with real-time changes and prettier formatting.

---

## Installation Instructions

### 1. Clone the repository:
```bash
git clone https://github.com/CFMVCarlos/TailwindCSS-Testing.git
cd TailwindCSS-Testing
```

### 2. Install Prettier with Tailwind CSS plugin:
```bash
npm install
```

---

## Usage Guide

### 1. Create the required configuration files:

#### a. **Prettier configuration (`prettier.config.js`):**
```javascript
module.exports = {
  plugins: ["prettier-plugin-tailwindcss"],
};
```

#### b. **Tailwind CSS configuration (`tailwind.config.js`):**
```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./*.html"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

### 2. Build Tailwind CSS:
Run the following command to build your Tailwind CSS file:
```bash
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

### 3. View the project:
Open your browser and navigate to [localhost](http://localhost:3000) to see the project in action.

---

### Additional Resources
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Prettier Documentation](https://prettier.io/docs/en/index.html)

## Author

- [Carlos Valente](https://github.com/CFMVCarlos)