# mina-client-connection

This is based on Mina's [tutorial](https://docs.minaprotocol.com/zkapps/tutorials/zkapp-ui-with-react) on browser UI. Connection logic is inside `index.page.tsx`.

## Steps

Build the contracts:

```bash
# 1
cd contracts
# 2
npm install
# 3
npm run build
```

Run the app:

```bash
# 1 (from project root directory)
cd ui
# 2
npm install
# 3
npm run dev
```

In another terminal tab:

```bash
# 1 (from project root directory)
cd ui
# 2
npm run ts-watch
```
