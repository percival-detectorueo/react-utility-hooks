# react-utility-hooks

A handful of React hooks I keep copy-pasting between projects

Started as a weekend hack, grew on me.

## Install

```bash
npm install
npm test
```

## What it does

- useDebounce with leading/trailing options
- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization
- Tiny: no dependencies besides React

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── SECURITY.md
└── package.json
```
