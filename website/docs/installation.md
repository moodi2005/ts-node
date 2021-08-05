---
title: Installation
---

```shell
# Locally in your project.
npm i -D typescript
npm i -D ts-node

# Or globally with TypeScript.
npm i -g typescript
npm i -g ts-node

# Depending on configuration, you may also need these
npm i -D tslib @types/node
```

**Tip:** Installing modules locally allows you to control and share the versions through `package.json`. TS Node will always resolve the compiler from `cwd` before checking relative to its own installation.
