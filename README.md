## About

This repository is about webpack build error when build content contains JavaScript expression literal as `/=/`,

and webpack will compile successfully in another usage `new RegExp('=')`.

```shell
pnpm install

pnpm build
```

> [build js expression literal /=/ error #17769](https://github.com/webpack/webpack/issues/17769)
