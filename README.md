1. Run commands

```bash
$ npm init -y
$ git init
```

1. Create files

- README.md
- .gitignore
  - node_modules
  - dist

1. Install dev dependencies

```bash
$ npm i -D jest
$ npm i -D typescript
$ npm i -D eslint
$ npm i -D prettier
```

1. Run init commands

```bash
$ npx jest --init
$ npx tsc --init
$ npx eslint --init
```

1. Hooks and linting

Husky [read more](https://www.npmjs.com/package/husky)

```bash
# install
$ npm i -D husky

# configure
$ npx husky install

# create hook
npx husky add .husky/pre-commit "npm test"

# test hook
git add .husky/pre-commit
git commit -m "Keep calm and commit"
# `npm test` will run
```
