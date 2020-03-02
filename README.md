# `ts-node` with Babel.

Let's use `babel-node` for TypeScript as easy as `ts-node`.

NOTE: this is just a small wrapper for `babel-node` and only resolves verbose arguments passed to `babel-node`. See the core [`/ts-node.sh`](https://github.com/shqld/ts-node/blob/master/ts-node.sh).

### Install

```sh
npm i -D @shqld/ts-node
yarn add -D @shqld/ts-node
```

### Usage

```json
{
  "scripts": {
    "do-task": "ts-node tasks/some-task.ts"
  },
  "devDepedencies": {
    "@babel/core": "7.x",
    "@babel/preset-typescript": "7.x",
    "@shqld/ts-node": "1.x"
  }
}
```

```sh
npx do-task
yarn do-task
```
