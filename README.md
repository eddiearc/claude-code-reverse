# Claude Code Reverse Engineering

## Claude Code folders

```
├── LICENSE.md
├── README.md
├── cli.mjs // here we go
├── node_modules // only @img/sharp
├── package.json
├── vendor // @anthropic-ai/sdk
└── yoga.wasm // for ink, the React-based CLI framework
```

## Deep Dive `@anthropic-ai/claude-code/cli.mjs

First, use `scripts/beautify.js` to output `cli.beautify.mjs`
