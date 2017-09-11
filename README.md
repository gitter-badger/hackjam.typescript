# Typescript Koans

[![Join the chat at https://gitter.im/hackages/hackjam.typescript](https://badges.gitter.im/hackages/hackjam.typescript.svg)](https://gitter.im/hackages/hackjam.typescript?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

In this set of examples and tests we cover typescript concepts by building a simple and lighter version of Lodash

By the end of this session you should know the following points:
-- How to type your code in TypeScript
-- interface and class 
-- Overloading of function
-- How to use default and optional parameters
-- Generics
-- Use npm or yarn for packaging your code 
-- How to use mocha for testing
-- TypeScript playground

### Quick start
**Make sure you have Node version >= 6.0 and NPM >= 3**

> Clone/Download the repo then edit `*.spec.js` files inside [`/test/`](/test/)

> Replace all `__` to fix failing tests

```bash
# clone our repo
git clone https://github.com/hackages/hackjam.typescript.git

# change directory to our repo
cd typescript.koans

# start the server 
yarn start

# start your tests in the console (`npm install` will be performed for you)
yarn test

```
go to [http://localhost:8080](http://localhost:8080) in your browser

**We use Mocha in this repository**

**For those using `yarn`, make sure to remove the `prestart` script before running `yarn**

**For those using **WallabyJS**, just run it and you'll be on your way to master JS syntax**

### TypeScript
> To take full advantage of TypeScript with autocomplete you would have to install it globally and use an editor with the correct TypeScript plugins.

#### Use latest TypeScript compiler
TypeScript 2.x.x includes everything you need. Make sure to upgrade, even if you installed TypeScript previously.

```
yarn global add typescript
```

#### Use a TypeScript-aware editor
We have good experience using these editors:

* [Visual Studio Code](https://code.visualstudio.com/)
* [Webstorm](https://www.jetbrains.com/webstorm/download/)
* [Atom](https://atom.io/) with [TypeScript plugin](https://atom.io/packages/atom-typescript)
* [Sublime Text](http://www.sublimetext.com/3) with [Typescript-Sublime-Plugin](https://github.com/Microsoft/Typescript-Sublime-plugin#installation)


## Contributing

Feel free to send us PRs

Happy coding!

[Hackages Team](http://hackages.io)
