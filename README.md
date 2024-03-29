<div align="center">

  <img src="https://camo.githubusercontent.com/0566752248b4b31b2c4bdc583404e41066bd0b6726f310b73e1140deefcc31ac/68747470733a2f2f692e636c6f756475702e636f6d2f7a6659366c4c376546612d3330303078333030302e706e67" alt="logo" width="200" height="auto" />
  <h1>ExpressJS Template</h1>

  <p>
    A simple ExpressJS template
  </p>

<!-- Badges -->
<p>
  <a href="https://github.com/DuckyMomo20012/express-template/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/DuckyMomo20012/express-template" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/DuckyMomo20012/express-template" alt="last update" />
  </a>
  <a href="https://github.com/DuckyMomo20012/express-template/network/members">
    <img src="https://img.shields.io/github/forks/DuckyMomo20012/express-template" alt="forks" />
  </a>
  <a href="https://github.com/DuckyMomo20012/express-template/stargazers">
    <img src="https://img.shields.io/github/stars/DuckyMomo20012/express-template" alt="stars" />
  </a>
  <a href="https://github.com/DuckyMomo20012/express-template/issues/">
    <img src="https://img.shields.io/github/issues/DuckyMomo20012/express-template" alt="open issues" />
  </a>
  <a href="https://github.com/DuckyMomo20012/express-template/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/DuckyMomo20012/express-template.svg" alt="license" />
  </a>
</p>

<h4>
    <a href="https://github.com/DuckyMomo20012/express-template/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/DuckyMomo20012/express-template">Documentation</a>
  <span> · </span>
    <a href="https://github.com/DuckyMomo20012/express-template/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/DuckyMomo20012/express-template/issues/">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->

# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  - [Screenshots](#camera-screenshots)
  - [Tech Stack](#space_invader-tech-stack)
  - [Features](#dart-features)
  - [Color Reference](#art-color-reference)
  - [Environment Variables](#key-environment-variables)
- [Getting Started](#toolbox-getting-started)
  - [Prerequisites](#bangbang-prerequisites)
  - [Run Locally](#running-run-locally)
  - [Running Tests](#test_tube-running-tests)
  - [Deployment](#triangular_flag_on_post-deployment)
- [Usage](#eyes-usage)
- [Roadmap](#compass-roadmap)
- [Contributing](#wave-contributing)
  - [Code of Conduct](#scroll-code-of-conduct)
- [FAQ](#grey_question-faq)
- [License](#warning-license)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)

<!-- About the Project -->

## :star2: About the Project

<!-- Screenshots -->

### :camera: Screenshots

<div align="center">
  <img src="https://placehold.co/600x400?text=Your+Screenshot+here" alt="screenshot" />
</div>

<!-- TechStack -->

### :space_invader: Tech Stack

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.javascript.com/">Javascript</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://expressjs.com/">Express.js</a></li>
  </ul>
</details>

<!-- Features -->

### :dart: Features

- Feature 1.
- Feature 2.
- Feature 3.

<!-- Color Reference -->

### :art: Color Reference

| Color           | Hex                                                              |
| --------------- | ---------------------------------------------------------------- |
| Primary Color   | ![#222831](https://placehold.jp/222831/222831/10x10.png) #222831 |
| Secondary Color | ![#393E46](https://placehold.jp/393E46/393E46/10x10.png) #393E46 |
| Accent Color    | ![#00ADB5](https://placehold.jp/00ADB5/00ADB5/10x10.png) #00ADB5 |
| Text Color      | ![#EEEEEE](https://placehold.jp/EEEEEE/EEEEEE/10x10.png) #EEEEEE |

<!-- Env Variables -->

### :key: Environment Variables

To run this project, you will need to add the following environment variables to
your `.env` file:

- **App configs:**

  `TEST_VAR`: Description of this environment variable.

E.g:

```
# .env
TEST_VAR="my secret key"
```

You can also check out the file `.env.example` to see all required environment
variables.

<!-- Getting Started -->

## :toolbox: Getting Started

<!-- Prerequisites -->

### :bangbang: Prerequisites

This project uses [pnpm](https://pnpm.io/) as package manager:

```bash
npm install --global pnpm
```

<!-- Run Locally -->

### :running: Run Locally

Clone the project:

```bash
git clone https://github.com/DuckyMomo20012/express-template.git
```

Go to the project directory:

```bash
cd express-template
```

Install dependencies:

```bash
pnpm install
```

Start the server:

```bash
pnpm start
```

OR:

Run with `nodemon`:

```bash
pnpm dev
```

---

Access server:

The server will run on: http://localhost:3000/

<!-- Running Tests -->

### :test_tube: Running Tests

To run tests, run the following command:

```bash
pnpm test
```

<!-- Deployment -->

### :triangular_flag_on_post: Deployment

To deploy this project to Render:

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/DuckyMomo20012/express-template)

<!-- Usage -->

## :eyes: Usage

Use this space to tell a little more about your project and how it can be used.
Show additional screenshots, code samples, demos, or links to other resources.

```javascript
const express = require('express');
const router = express.Router();

/* GET home page. */
router.get('/', (req, res, next) => {
  res.render('index', { title: 'Express' });
});

module.exports = router;
```

<!-- Roadmap -->

## :compass: Roadmap

- [x] Todo 1.
- [ ] Todo 2.

<!-- Contributing -->

## :wave: Contributing

<a href="https://github.com/DuckyMomo20012/express-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=DuckyMomo20012/express-template" />
</a>

Contributions are always welcome!

<!-- Code of Conduct -->

### :scroll: Code of Conduct

Please read the [Code of Conduct](https://github.com/DuckyMomo20012/express-template/blob/main/CODE_OF_CONDUCT.md).

<!-- FAQ -->

## :grey_question: FAQ

- Question 1

  - Answer 1.

- Question 2

  - Answer 2.

<!-- License -->

## :warning: License

Distributed under MIT license. See
[LICENSE](https://github.com/DuckyMomo20012/express-template/blob/main/LICENSE)
for more information.

<!-- Contact -->

## :handshake: Contact

Duong Vinh - [@duckymomo20012](https://twitter.com/duckymomo20012) -
tienvinh.duong4@gmail.com

Project Link: [https://github.com/DuckyMomo20012/express-template](https://github.com/DuckyMomo20012/express-template).

<!-- Acknowledgments -->

## :gem: Acknowledgements

Here are useful resources and libraries that we have used in our projects:

- [Awesome Readme Template](https://github.com/Louis3797/awesome-readme-template):
  A detailed template to bootstrap your README file quickly.
