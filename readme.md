<h1 align="center">VaultWorker: Secure client side storage</h1>

<p align="center">
    &nbsp;<img src="https://img.shields.io/badge/made%20by-YenHub%20💚-blue" />
    &nbsp;<img src="https://badgen.net/badge/icon/typescript?icon=typescript&label" />
    &nbsp;<img src="https://badgen.net/badge/icon/vscode?icon=visualstudio&label" />
    &nbsp;<img src="https://badgen.net/badge/icon/github?icon=github&label" />
    &nbsp;<img src="https://badgen.net/badge/icon/npm?icon=npm&label" />
</p>

<p align="center">
    &nbsp;<img src="https://img.shields.io/github/last-commit/YenHub/vault-worker?color=brightgreen" />
    &nbsp;<img src="https://img.shields.io/github/issues-raw/YenHub/vault-worker?color=brightgreen" />
    &nbsp;<img src="https://img.shields.io/github/repo-size/yenhub/vault-worker?color=brightgreen" />
</p>

> 🚧 **BETA VERSION**\
> \
> This package is currently considered to be in early BETA and should be used with caution.\
> We didn't break it if you didn't use it!! 😏

VaultWorker is a client side, secure storage implementation using the WebWorker and MessageChannel APIs.

The aim of this project is to provide a secure method to store and retrieve data in the browser.

## Dev Tips

### Working with the package locally

Simply use `npm link` when working with this package locally.

There is no need to install this package locally using `npm i @yenhub/vault-worker`.

You may do this however when consuming a published version of this package.

```bash
# From the root of this project
yarn build && npm link

# In the project you are testing the dependency against
npm link @yenhub/vault-worker
```

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create.

Any contributions you make are **greatly appreciated** 🤗

1. Fork the Project
2. Create your Feature Branch: `git checkout -b feature/super-cool-new-feature`
3. Commit your Changes: `git commit -m '💥 Adds super cool new feature'`
4. Push to the Branch: `git push origin feature/super-cool-new-feature`
5. Open a Pull Request and enjoy yourself a nice 🍺🍷
