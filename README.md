# 📝 Lexical Playground Editor Component

A beautifully crafted, fully-featured rich text editor component extracted from the official [Lexical Playground](https://github.com/facebook/lexical) by Meta. This package wraps the Lexical demo editor into a standalone, reusable React component that can be easily integrated into your applications.

---

## ✨ Features

- ⚛️ Built with **React** and **Lexical**
- 🔤 Rich text formatting
- 📋 Clipboard support (copy/paste)
- 🖼️ Image, link, and code block support
- 🧱 Plugin architecture: Youtube video, Links, Code, Comment, Drag & Drops, Image editor with Exclidraw, Emoji, Equation, Image, Markdown, Mention, Page Break, Table, Sticker, Twitter, ...
---

## Usage

```ts
import { Editor } from 'lexical-playground'; 

function MyComponent (){
    return  <Editor
        showTreeView={false}
        showNestedEditorTreeView={false}
        showTableOfContents={false}
        shouldAllowHighlightingWithBrackets={false}
        initialState={initialState}
      />
}
```

## 📦 Installation

```bash
npm install lexical-playground-editor
# or
yarn add lexical-playground-editor
