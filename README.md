# ds30-mockup

Minimal design system component library for AI-powered prototyping.

## 🚀 Getting Started

```bash
npm install
npm run tokens:build
npm run dev
```

## 📁 Project Structure

```
ds30-mockup/
├── src/
│   ├── components/      # UI components
│   ├── tokens/          # Design tokens (JSON)
│   ├── styles/          # Generated CSS variables
│   └── index.ts         # Entry point
├── tokens/              # Token configuration
└── dist/                # Build output
```

## 🎨 Design Tokens

Tokens are defined in `src/tokens/` as JSON files.

Build CSS variables:
```bash
npm run tokens:build
```

## 📦 Building

```bash
npm run build
```
