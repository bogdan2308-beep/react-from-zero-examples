# React from Zero — Working Examples

*Code examples from the book [React from Zero](https://www.amazon.com/dp/B0HKHZ2DM8) by Jack Mercer.*

## Overview

This repository contains five minimal, runnable React examples that correspond to Chapters 1-5 of *React from Zero*. Each example is a standalone HTML file that uses [unpkg](https://unpkg.com) and [Babel](https://babeljs.io) to render React in the browser — no build step required.

## Examples

| # | Example | Concept | Book Chapter |
|---|---------|---------|------------|
| [01](01-hello-react) | Hello React | First component, `React.createElement` | 1 |
| [02](02-components) | Components | Function components with props | 2 |
| [03](03-state) | State | `useState` hook, counter | 3 |
| [04](04-hooks) | Custom Hooks | `useFetch` for data fetching | 4 |
| [05](05-routing) | Routing | `BrowserRouter` + `React Router` | 5 |

## Quick Start

Each example runs in any modern browser. Open `index.html` and the React component will render automatically.

```html
<!-- Example: 01-hello-react -->
<script src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
<script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
<!-- Then open 01-hello-react/index.html in a browser -->
```

## Attribution

Built with *React from Zero* by [Jack Mercer](https://www.amazon.com/dp/B0HKHZ2DM8).
