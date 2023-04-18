<a name="readme-top"></a>
<div align="center">

  ![Project Banner](readme_assets/readme_banner.png#gh-dark-mode-only)
  ![Project Banner](readme_assets/readme_banner-light.png#gh-light-mode-only)

  <h1>TSNode & MongoDB REST API</h1>
  
  <p>
    well-structured boilerplate for REST API using Node.js, TypeScript, Express & MongoDB.
  </p>

<!-- Badges -->
<p>
  <a href="https://github.com/ladunjexa/TSNode-MongoDB-REST-API/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/ladunjexa/TSNode-MongoDB-REST-API" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/ladunjexa/TSNode-MongoDB-REST-API" alt="last update" />
  </a>
  <a href="https://github.com/ladunjexa/TSNode-MongoDB-REST-API/network/members">
    <img src="https://img.shields.io/github/forks/ladunjexa/TSNode-MongoDB-REST-API" alt="forks" />
  </a>
  <a href="https://github.com/ladunjexa/TSNode-MongoDB-REST-API/stargazers">
    <img src="https://img.shields.io/github/stars/ladunjexa/TSNode-MongoDB-REST-API" alt="stars" />
  </a>
  <a href="https://github.com/ladunjexa/TSNode-MongoDB-REST-API/issues/">
    <img src="https://img.shields.io/github/issues/ladunjexa/TSNode-MongoDB-REST-API" alt="open issues" />
  </a>
  <a href="https://github.com/ladunjexa/TSNode-MongoDB-REST-API/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/ladunjexa/TSNode-MongoDB-REST-API.svg" alt="license" />
  </a>
</p>
   
 <h4>
    <a href="https://ai-powered-3-d-product-web.vercel.app/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/ladunjexa/TSNode-MongoDB-REST-API">Documentation</a>
  <span> · </span>
    <a href="https://github.com/ladunjexa/TSNode-MongoDB-REST-API/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/ladunjexa/TSNode-MongoDB-REST-API/issues/">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->
<details>

<summary>

# :notebook_with_decorative_cover: Table of Contents

</summary>

- [About the Project](#star2-about-the-project)
  * [Folder Structure](#bangbang-folder-structure)
  * [Tech Stack](#space_invader-tech-stack)
- [Getting Started](#toolbox-getting-started)
  * [Environment Variables](#key-environment_variables)
  * [Installation](#gear-installation)
  * [Run Locally](#running-run-locally)
- [Contributing](#wave-contributing)
- [License](#warning-license)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)

</details>  

<!-- About the Project -->
## :star2: About the Project

<!-- <div align="center">
  <img src="readme_assets/mock.png" height="auto" width="90%"/>
</div> -->

This repository houses a well-structured REST API for ***User Management*** powered by MongoDB with cookie based authentication, with the abilities to Create, Read, Update users.
REST API built with TypeScript, Node.js, Express & MongoDB.

<!-- Folder Structure -->
### :bangbang: Folder Structure

Here is the folder structure of REST API.
```bash
TSNode-MongoDB-REST-API/
|- server/
  |-- src/
    |-- controllers/
    |-- db/
    |-- helpers/
    |-- middlewares/
    |-- router/
    |-- index.ts
  |-- .env
  |-- nodemon.json
  |-- tsconfig.json
  |-- package.json
```
<br />

<!-- TechStack -->
### :space_invader: Tech Stack

[![My Skills](https://skillicons.dev/icons?i=ts,nodejs,express,mongodb)](https://skillicons.dev)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Getting Started -->
## :toolbox: Getting Started

<!-- ENV VARIABLES -->
### :key: Environment Variables

In order to use this REST API you have to add some environment variables to .env file,

##### _server-side_ [server/.env]
create `.env` file in `server/` directory & add the following environment variables:
```env
SESSION_TOKEN_NAME=<SESSION_TOKEN_NAME>
MONGODB_URL=<MONGODB_URL>
SECRET=<REST_API_SECRET>
PORT=<PORT> // optional, default set to 8080
```

<!-- Installation -->
### :gear: Installation

#### Step 1:
Download or clone this repo by using the command below:

```bash
 https://github.com/ladunjexa/TSNode-MongoDB-REST-API.git
```

#### Step 2:

This REST API using NPM (Node Package Manager), therefore, make sure that Node.js is installed by execute the following command in console: (minimum Node 14.x)

```bash
  node -v
```

#### Step 3:

In `server` folder execute the following command to get the required packages:

```bash
  npm install
```

<!-- Run Locally -->
### :running: Run Locally

#### Step 1:

Go to `server` folder and execute the following command in order to start the server:

```bash
  npm start
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/ladunjexa/TSNode-MongoDB-REST-API/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ladunjexa/TSNode-MongoDB-REST-API" />
</a>


Contributions are always welcome!

See [`contributing.md`](https://contributing.md/) for ways to get started.

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- License -->
## :warning: License

Distributed under the MIT License. See [LICENSE.txt](https://github.com/ladunjexa/TSNode-MongoDB-REST-API/blob/main/LICENSE) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Contact -->
## :handshake: Contact

Liron Abutbul - [@lironabutbul6](https://twitter.com/lironabutbul6) - [@ladunjexa](https://t.me/ladunjexa)

Project Link: [https://github.com/ladunjexa/TSNode-MongoDB-REST-API](https://github.com/ladunjexa/TSNode-MongoDB-REST-API)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Acknowledgments -->
## :gem: Acknowledgements

This section used to mention useful resources and libraries that used in the REST API:

#### server-side

- [Body Parser](https://www.npmjs.com/package/body-parser)
- [Compression](https://www.npmjs.com/package/compression)
- [Cookie Parser](https://www.npmjs.com/package/cookie-parser)
- [CORS](https://www.npmjs.com/package/cors)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [Express.js](https://expressjs.com/)
- [lodash](https://lodash.com/)
- [mongoose.js](https://mongoosejs.com/)
- [Nodemon](https://www.npmjs.com/package/nodemon)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
