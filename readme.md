This file will have conflicts

conflict

```ts
const mapLevelToMethod = {
  silly: 0,
  trace: 1,
  debug: 2,
  info: 3,
  warn: 4,
  error: 5,
  fatal: 6,
};

const level = mapLevelToMethod[process.env.LOG_LEVEL.toLower() || "info"];
```

```ts
const mapLevelToMethod = {
  silly: 0,
  trace: 1,
  debug: 2,
  info: 3,
  warn: 4,
  error: 5,
  fatal: 6,
};

const level = mapLevelToMethod[process.env.LOG_LEVEL.toLower() || "info"];
```

```ts

```
