# Note: Project archived in favor of nx

I found out about https://nx.dev/ and will be using that in the future:

```
npx create-nx-workspace --preset=ts
npm install --save-dev @nrwl/node
nx generate @nrwl/node:app cli
nx serve cli
```

<hr />

# README

## Compile and watch

```
npx tsc -w
```

or

```
npx tsc-watch --project . --onSuccess 'ts-node ./dist/index.js'
```
