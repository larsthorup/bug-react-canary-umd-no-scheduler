# bug-react-canary-umd-no-scheduler

```bash
npm install
open index.html
```

Gives:

```
Uncaught TypeError: _ReactInternals$Sched is undefined
react-dom.development.js:535:33
```

Downgrading to v18.2 doesn't have this issue:

```
npm install react@latest react-dom@latest
```