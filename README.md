# TypeScript Starter Kit

This is an opinionated TypeScript Starter kit to help kick-start development of your next npm package.

## 💡 Get Started

Luckily, it's incredibly easy to get your package development started with this slightly opinionated starter kit.

```bash
# you may use this GitHub template or the following command:
npx degit openweblabs/ts-starter my-pkg
cd my-pkg

 # if you don't have pnpm installed, run `npm i -g pnpm`
pnpm i # install all deps
pnpm build # builds the library for production-ready use
```

### 👩🏽‍💻 Dev Tools

- [TypeScript 4.6](https://www.typescriptlang.org/)
- [unbuild](https://vitejs.dev/) - "Next Generation Frontend Tooling"
- [Commitizen & commitlint](https://www.npmjs.com/package/@commitlint/cz-commitlint) - Automate git commits, versioning, and CHANGELOG generation
- [Vitest](https://github.com/vitest-dev/vitest) - Unit testing powered by Vite
- [Renovate](https://renovatebot.com/) - automatic PR dependency updates
- [GitHub Actions](https://github.com/features/actions) - automatically fixes code style issues, tags releases, and runs the test suite
- [ESLint](https://eslint.org/) - statically analyzes your code to quickly find problems
- [VS Code Extensions](./.vscode/extensions.json)
  - [cspell](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) - spell checking

### Tips

This project includes a simple way to handle & automate your "versioning." Through semantic commit names, two separate changelogs are generated upon a release: one as part of the GitHub releases & the other one as a markdown file that's created within the root of the project.

```bash
# how to create a git commit?
git add . # select the changes you want to commit
pnpm run commit # then simply answer the questions

# after you have successfully committed, you may create a "release"
pnpm run release # automates git commits, versioning, and CHANGELOG generation

# how to test your library locally?
pnpm pack # packs the library into a tarball
```

## 🧪 Testing

```bash
pnpm test
```

## 📈 Changelog

Please see our [releases](https://github.com/meemalabs/ts-starter/releases) page for more information on what has changed recently.

## 💪🏼 Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## 🏝 Community

For help, discussion about best practices, or any other conversation that would benefit from being searchable:

[Discussions on GitHub](https://github.com/openweblabs/ts-starter/discussions)

For casual chit-chat with others using this package:

[Join the Open Web Discord Server](https://discord.ow3.org)

## 📄 License

The MIT License (MIT). Please see [LICENSE](LICENSE.md) for more information.

Made with ❤️ by Open Web Labs.
