<div align="center">
  <h1><code>Game of life</code></h1>

  <strong>Conway's Game of Life built in Typescript</strong>
    
  <p>
    <a href=""><img src="https://img.shields.io/azure-devops/build/rustwasm/gloo/6.svg?style=flat-square" alt="Build Status" /></a>
    <a href=""><img src="https://codecov.io/gh/SBoudrias/Inquirer.js/branch/master/graph/badge.svg" alt="Coverage Status" /></a>
    <a href=""><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome" /></a>
  </p>
  
  <img src="https://user-images.githubusercontent.com/18004357/131463806-e5286d9c-3acd-4274-a52d-9718953a0495.gif">
  <h3>
    <a href="https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors">Contributing</a>
    <span>
  </h3>
  <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
  <br />
  <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
  ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
  ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>

</p>

</div>

## Table of Contents

- [About](#about)
  - [Built with](#built-with)
  - [Rules](#rules)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installing](#installing)
- [Usage examples](#usage-examples)
 - [Patterns to explore](#patterns)
- [Contact](#contact)
- [License](#license)
- [Acknowledgements](#acknowledgements)


## About <a name="about"></a>

_Cекция содержит краткое описание вашего проекта. Вдохновение, идеи, мотивация, которые послужили началом для создания._

__[The Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)__, also known simply as __Life__, is a cellular automaton devised by the British mathematician *John Horton Conway* in 1970.

It is a zero-player game, meaning that its evolution is determined by its initial state, requiring no further input. One interacts with the __Game of Life__ by creating an initial configuration and observing how it evolves. 

<div align="center">
  <img src="https://user-images.githubusercontent.com/18004357/131469221-79bf2cdb-4d43-418c-b954-8d9292481646.gif">
</div>

### Built with <a name="built-with"></a>

_Секция содержит используемые в проекте технологии. Если их слишком много следует оставлять наиболее крупные из них._

<p align="center"><a href="https://babeljs.io/" target="_blank">
  <img src="https://www.vectorlogo.zone/logos/babeljs/babeljs-icon.svg" alt="babel" width="60" height="60"/> </a> <a href="https://www.w3schools.com/css/" target="_blank"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="60" height="60"/> </a> <a href="https://git-scm.com/" target="_blank"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="60" height="60"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="60" height="60"/> </a> <a href="https://jestjs.io" target="_blank"> 
  <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="60" height="60"/> </a> <a href="https://reactjs.org/" target="_blank"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="60" height="60"/> </a> <a href="https://redux.js.org" target="_blank"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" width="60" height="60"/> </a>
</p>

### Rules <a name="rules"></a>

1. Any live cell with fewer than two live neighbours dies, as if by underpopulation.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

These rules, which compare the behavior of the automaton to real life, can be condensed into the following:

1. Any live cell with two or three live neighbours survives.
2. Any dead cell with three live neighbours becomes a live cell.
3. All other live cells die in the next generation. Similarly, all other dead cells stay dead.

## Getting started <a name="getting-started"></a>

_Пример того, как вы можете дать инструкции или первоначальные требования пользователю для корректной установки и запуска проекта._

### Prerequisites <a name="prerequisites"></a>

:warning: Before installing the project latest version of __npm__ should be installed.

```
npm install -g npm@latest
```

### Installing <a name="installing"></a>

1. Clone the repo

```
git clone https://github.com/your_username_/GameOfLife.git
```
2. Install NPM packages

```
npm install
```
3. Start the project

```
npm start
```

## Usage examples <a name="usage-examples"></a>

_В этой секции могут содержаться полезные примеры использования проекта. Блоки кода, изображения и анимации. Сюда можно приложить ссылки на дополнительные ресурсы._

```ts
/* Creating new instance of Game of life */

const options: GameOpts = {
  width: 10,
  height: 10
};

const newGame = new GameOfLife(options);
```

### Patterns you can explore <a name="patterns"></a>

<img src="https://user-images.githubusercontent.com/18004357/131480947-09cc9a2a-fef6-40e5-abf2-04c090d92e1c.png" />

## Contact <a name="contact"></a>

[![LinkedIn][linkedin-shield]][linkedin-url]

## License <a name="license"></a>

[![MIT License][license-shield]][license-url]

## Acknowledgements <a name="acknowledgements"></a>

- [Choose a license](https://choosealicense.com/)
- [img.shields](https://shields.io/category/social)

<div align="center">
  <sub>Built with :heart: by Passionate Otus Student</sub>
</div>



[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/username

