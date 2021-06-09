<p align="center">
  <a href="https://orbita.eduzz.com/">
    <img alt="Hermes Notes" title="Hermes" src="src/assets/icon.png">
  </a>
</p>

<h1 align="center">Hermes Notes</h1>

<p align="center">Simple backend created for an app used as work for college with Express</p>


## :hammer: **Stack**

- [Expo](https://expressjs.com/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

## :white_check_mark: **Prerequisites**

Before you start, you will need to install in your machine the follow tools:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) and [Yarn](https://yarnpkg.com/).
Besides, it's interesting to use an IDE as [VSCode](https://code.visualstudio.com/)

## :keyboard: **Developing**

```bash
# Clone this repo
$ git clone https://github.com/miguelaugl/hermes-backend.git

# Enter project
$ cd hermes-backend

# Install dependencies
$ yarn

# Execute the application
$ yarn dev

# The server will start at port 3333 by default. Access: <http://localhost:3333>
```

## :construction_worker: **Architecture**

```text
.
├── ...
├── src
│   ├── @types          # TypeScript declares or overrides
│   ├── assets          # Folder for media
│   ├── components
│   │   ├── pages       # App screens
│   │   └── shared      # Shared components
│   ├── helpers         # Generics Functions or variables that have multiple use cases
│   ├── services        # External libraries communication or api calls
│   └── ...
└── ...
```
