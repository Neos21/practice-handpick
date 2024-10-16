# Practice Handpick

Practice [Handpick](https://github.com/henryruhs/handpick)

```bash
$ npm install --global handpick

# dependencies, devDependencies
$ handpick
  $ npm install --include-dev

# lintDependencies Only
$ handpick --target=lintDependencies
  $ npm run install-with-lint

# dependencies, devDependencies, lintDependencies
$ handpick --target=dependencies --target=devDependencies --target=lintDependencies
  $ npm run install-only-lint
```


## Links

- [Neo's World](https://neos21.net/)
