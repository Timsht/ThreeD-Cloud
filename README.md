# Three D Cloud

![Three D Cloud](.github/images/ThreeDCloud.gif 'Three D Cloud')

## Requirements

- [yarn](https://classic.yarnpkg.com/lang/en/docs/install/ 'yarn') : install dependencies using yarn
- [yalc](https://github.com/wclr/yalc 'yalc') : package development and simulating the publishing and installation of packages.

## Install

First install dependencies by running

```shell
yarn
```

### Building

Build package with tsup with production

```shell
yarn build
```

### Developing

Watch and rebuild code with tsup and runs Storybook to preview your UI during development.

```shell
yalc add three-d-cloud
```

Link your package to your development project by simulating package manage by using `yalc`

```shell
yalc add three-d-cloud
```

or

```shell
npx yalc link three-d-cloud
```

Run tests with `jest` when changes are detected

```shell
yarn test:watch
```

## Features

- [ ] Use dynamically react nodes surround by ThreeDCloud tag
- [ ] Customize speed with props
- [ ] Customize size with props
- [ ] Customize depth with props
- [ ] Customize className with props
- [ ] Storybook customization
- [ ] Tests

## Contributing

Contributions are always welcome! See [CONTRIBUTING.md](CONTRIBUTING.md 'CONTRIBUTING.md') for ways to get started.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Credit

- This project is strongly inspired from [TagCloud](https://github.com/cong-min/TagCloud 'TagCloud'). You will retrieve the main logic in TagCloud project but its written in JavaScript.
- The structure and tools is inspired from [tsup react package starter](https://github.com/TimMikeladze/tsup-react-package-starter 'tsup react package starter') which is a boilerplate for create, build & publish React packages with TypeScript on public repository.
