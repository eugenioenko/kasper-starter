# Kasper.js

A lightweight component framework with fine-grained signal-based reactivity and single-file components.

[**Get Started**](https://kasper.top) | [**View on GitHub**](https://github.com/eugenioenko/kasper-js)

Kasper.js is a lightweight framework for building reactive web UIs. It sits between simple templating engines and full frameworks like Vue or React — small enough to understand completely, powerful enough for real applications.

## Key Features

### ⚡ Fine-grained Signals
Reactive primitives that update only the exact DOM nodes that depend on them. No virtual DOM, no diffing, no full re-renders.

### 📦 Single-file Components
Write `<template>`, `<script>`, and `<style>` in a single `.kasper` file. Powered by a Vite plugin with full TypeScript support.

### 🧠 Rich Expression Language
Arrow functions, pipeline operator `|>`, optional chaining, spread, and more — a proper AST-based expression interpreter, not `eval`.

### 🛠️ Template Directives
`@if`, `@each`, `@while`, `@let`, `@attr`, `@ref` — valid HTML attributes with surgical DOM updates and automatic cleanup.

### 🤖 AI Agent Ready
56KB, zero dependencies, entire API fits in a single context window. Paste `llms.txt` into any agent and it can write idiomatic Kasper code from scratch.

### 📘 TypeScript First
Written in TypeScript, ships declaration files. Full type checking and autocomplete out of the box.

---

For more information, visit the official documentation: [kasper.top](https://kasper.top)
