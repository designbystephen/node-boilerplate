# node-boilerplate
> A boilerplate featuring common configurations, dependencies and functionality to provide a quick start for your next project.

# Requirements
- Node `v14.x`
  - `v14.16` at the time of this document creation
  - https://nodejs.org/en/download/
- Yarn `v2.x`
  - `v2.4` at the time of this document creation
  - https://yarnpkg.com/getting-started/install

# Getting Started
- Clone or fork this repo `git clone https://github.com/designbystephen/node-boilerplate.git`
- Change to project root `cd my-project-directory`
- Install dependencies `yarn`
- Start writing code in `my-project-directory/src`

# Features

## Compilation / Transpilation
- babel
  - @babel/cli
  - @babel/core
  - @babel/node
  - @babel/plugin-transform-runtime
  - @babel/preset-env
  - @babel/register

## Envrionment Variables
- dotenv (.env) support
  - create-react-app style envrionment variables via `universal-dotenv`

## Linting
- `eslint`
  - airbnb core linting styles via `eslint-config-airbnb-base`

## Unit Testing
- `mocha`
  - Lightweight testing framework
- `expect`
  - Jest style assertions
- `nock`
  - Request interception useful for testing REST apis

## Git Hooks
- `husky`
  - Linting at pre-commit
  - customizable for other git hooks

# Workspaces

## Visual Studio Code
- typical workspace settings configured in `.vscode` within the project root

# Scripts
| Command | Description |
| :-------------: | :----------: |
| `yarn test` | Run unit tests |
| `yarn lint` | Run linter |
| `yarn build` | Build `/src` to `/build` directory |
| `yarn start` | Run application at `/src/index` |
