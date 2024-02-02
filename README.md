<div align="center">

<img src="./public/icon.png" style="width:82px;"/>

# Calcium Calculator

[![Author](https://img.shields.io/badge/Author-NriotHrreion-red.svg "Author")](https://github.com/NriotHrreion)
[![LICENSE](https://img.shields.io/badge/License-MIT-green.svg "LICENSE")](./LICENSE)
[![Stars](https://img.shields.io/github/stars/nocpiun/calcium.svg?label=Stars&style=flat)](https://github.com/nocpiun/calcium/stargazers)
[![Github Workflow Status](https://img.shields.io/github/actions/workflow/status/nocpiun/calcium/test.yml)](https://github.com/nocpiun/calcium/actions/workflows/test.yml)
[![Netlify Status](https://api.netlify.com/api/v1/badges/41b2bd01-9404-4d8b-99c4-7dea623f720a/deploy-status)](https://app.netlify.com/sites/courageous-bublanina-6857c1/deploys)

> A web-based calculator app

</div>

![Banner](./images/banner.png)

## Description

Calcium is a web-based calculator written in React + Typescript.

If you have any problem or idea, it's welcome to open an issue to let me know.

_[Here is the Wiki](https://github.com/nocpiun/calcium/wiki)_

_[Here is the Manual](https://github.com/nocpiun/calcium/wiki/Manual)_

#### Why its name is Calcium?

```
Calculator -> calc -> Ca (Chemical Element) -> Calcium
```

#### What features does it include?

- Basic calculating
- Sigma & Integral & Product calculating
- Variable creating and storing
- Function Images Graphing
- Base conversion
- Unit conversion
- Relationship calculating (Thanks to [relationship.js](https://github.com/mumuy/relationship))
- History recording

## Deploy & Use

**It's recommended to access Calcium by [calcium.js.org](https://calcium.js.org). But if you want to deploy it locally, please continue reading the following text.**

#### Docker

First, you need to make sure that your server (or computer) has installed [Docker](https://docker.com).

1. Pull docker repository

```bash
docker pull noahhrreion/calcium:main
```

2. Create container

```bash
docker run -p 3000:3000 noahhrreion/calcium:main
```

3. Enter `http://localhost:3000`, and you can start using Calcium.

#### Launch directly

First, you need to make sure that your server (or computer) has installed [Git](https://git-scm.com/downloads) & [Node.js](https://nodejs.org/en/download).

1. Clone Git repo

```bash
git clone https://github.com/nocpiun/calcium.git
```

2. Install dependencies

```bash
npm i
```

If it throws error at this step, you can try:

```bash
npm i --force
```

3. Launch Calcium

```bash
npm run start
```

4. Enter `http://localhost:3000`, and you can start using Calcium.

5. If you want to make contribution to this repo, then you can set out to modify the code and start debugging!

## Contributing

Contributions to Calcium are welcomed. You can fork this project and start your contributing. If you don't know how to do, please follow the instruction [Creating a Pull Request from a Fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork). And I'll check the Pull Request list in my spare time. I can't make sure that every Pull Request will be checked at once.

Also, you're supposed to run tests before submitting a commit to your PR.

```bash
npm run test
```

## Scripts

An explanation of the `package.json` scripts.

- **`start`** Launch the app
- **`build`** Create a production build
- **`test`** Run tests

## LICENSE

[MIT](./LICENSE)
