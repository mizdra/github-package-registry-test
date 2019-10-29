# ts-node-skeleton

Boilerplate for ts-node.

## What's included

- ts-node
- TypeScript
- Prettier
- Recommended VSCode configuration

## Usage

```bash
## Clone boilerplate
git clone git@github.com:mizdra/ts-node-skeleton.git github-package-registry-test

## If project already exist...
cd github-package-registry-test
wget -O - https://github.com/mizdra/ts-node-skeleton/archive/master.tar.gz | tar xzvf - --strip=1

## Init project
rm yarn.lock
yarn install
yarn dev

```

## License

MIT

# github-package-registry-test

The test project for GitHub Package Registry 

## How to dev

- `yarn run start`: Run `src/index.ts`
- `yarn run check`: Try compile, lint, and format project
