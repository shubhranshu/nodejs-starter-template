# NodeJs CLI Starter template

Starter template to get going ith NodeJs CLI development withoutuch fuss.

Configured tooling

- [x] ES6 support with babel
- [x] Test script with Ava
- [x] Watch scripts for run and tests
- [x] Babel, Prettier and Eslint configs

## Usage and Configuration

Using this template to initialise repository or copy the files as required. Or simply use it to get some inspiration.

### Scripts

- **build** : `Build the project and copy the built files to dist folder`
- **test** : `Run ava tests`
- **watch-test** : `Watch code and run tests on code change`
- **cli-run** : `Run the code without building`
- **watch-run** : `Use nodemon to watch code and run on change`

### Packages

We are using [Yarn](https://github.com/yarnpkg/yarn) as the default package manager. To use [npm](https://github.com/npm/cli) delete [yarn.lock](yarn.lock) and run `npm install`

- [chalk](https://github.com/chalk/chalk)
- [inquirer](https://github.com/SBoudrias/Inquirer.js)
- [progress](https://github.com/visionmedia/node-progress)

Dev dependencies

- [ava](https://github.com/avajs/ava)
- [babel](https://github.com/babel/babel)
- [eslint](https://github.com/eslint/eslint)
- [nodemon](https://github.com/remy/nodemon)


## To Do

- [ ] Being able to parameterise the setup
- [ ] Options for Test framework
- [ ] CLI setup without using the repository
