# eoscr-components

[![N|Solid](https://eoscostarica.io/wp-content/uploads/2019/06/EOSCr-logo.png)](https://eoscostarica.io/)

A collection of React Components for EOSIO.

## Table of Contents

* [Installation](#installation)
* [Components](#components)
* [Run locally](#run-locally)
* [File Structure](#file-structure)
* [License](#license)
* [Contributors](#contributors)

## Version
- 0.1.0

### Installation
Install the dependencies and devDependencies and start the server.

```
$ npm install eoscr-components --save
```

## Components

|                |Description                          |Tag                        |
|----------------|-------------------------------|-----------------------------|
|Create Account | Form to create a new account          |`<CreateAccount />`           |
|Input Text          |Input Text           |`<InputText />`            |
|Modal          |Simple modal component |`<Modal />`|

## Run locally
### Development

Local development is broken into two parts (ideally using two tabs).

First, run rollup to watch your `src/` module and automatically recompile it into `dist/` whenever you make changes.

```
npm start
```

The second part will be running the `example/` create-react-app that's linked to the local version of your module.

```
# (in another tab)
cd example
npm start
```

Now, anytime you make a change to your library in `src/` or to the example app's `example/src`, `create-react-app` will live-reload your local dev server so you can iterate on your component in real-time.

![](https://media.giphy.com/media/12NUbkX6p4xOO4/giphy.gif)

## File Structure
Within the download you'll find the following directories and files:

```
eoscr-components/
├── README.md
├── example
│   ├── public
│   │   ├── index.html
│   │   └── manifest.json
│   ├── src
│   │   ├── App.js
│   │   ├── index.css
│   │   ├── index.js
│   │   └── infoComponent.js
│   ├── README.md
│   └── package.json
├──  src
│   ├── CreateAccount.js
│   ├── index.js
│   ├── InputText.js
│   └── Modal.js
├── .eslintrc
├── .gitignore
├── .prettierignore
├── prettier.config.js
└── package.json
```
## License

MIT © [EOS Costa Rica](https://eoscostarica.io)

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):
<table>
  <tr>
    <td align="center"><a href="https://github.com/xavier506"><img src="https://avatars0.githubusercontent.com/u/5632966?v=4" width="100px;" alt="Xavier Fernandez"/><br /><sub><b>Xavier Fernandez</b></sub></a><br /><a href="#ideas-xavier506" title="Ideas, Planning, & Feedback">🤔</a> <a href="#blog-xavier506" title="Blogposts">📝</a> <a href="#talk-xavier506" title="Talks">📢</a> <a href="#infra-xavier506" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
 <td align="center"><a href="https://github.com/tetogomez">
      <img src="https://avatars3.githubusercontent.com/u/10634375?s=460&v=4" width="100px;" alt="Teto Gomez"/><br /><sub><b>Teto Gomez</b></sub></a><br /><a href="https://github.com/eoscostarica/eosrate/commits?author=tetogomez" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/eoscostarica/eosrate/commits?author=tetogomez" title="Code">💻</a> <a href="#review-tetogomez" title="Reviewed Pull Requests">👀</a></td>
  </tr>
</table>

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!

