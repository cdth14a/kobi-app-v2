# Electron React Webpack Typescript - Boilerplate (2020)

Minimal boilerplate for writing Desktop Applications using Electron, React, Webpack & TypeScript.

This project makes use of latest packages like `electron`, `react`, `typescript` & `webpack` to serve the best environment for development.

<br>

## Core Features

- 🌟 ElectronJS
- 🌀 TypeScript
- 🎨 CSS Loader
- 🧹 ESLint
- 💪 ReactJS
- 🔱 Webpack & Configuration
- 🔥 Hot Module Replacement (Live Reload)
- 🎁 Package Bundling (Distribution / Release)

<br />

## Installation

#### To install this boilerplate you need to run following commands

Clone the repository on your hard drive :

```bash
git clone https://github.com/codesbiome/electron-react-webpack-typescript-2020

cd electron-react-webpack-typescript-2020
```

Install dependencies using Yarn or NPM :

```bash
yarn install
```

<br />

## Start : Development

#### To develop and run your application, you need to run following command

Start electron application for development :

```bash
yarn start
```

<br />

## Lint : Development

#### To lint application source code using ESLint via this command :

```bash
yarn lint
```

<br />

## Package : Production

Customize and package your Electron app with OS-specific bundles (.app, .exe, etc.)

```bash
yarn package
```

<br />

## Make : Production

Making is a way of taking your packaged application and making platform specific distributables like DMG, EXE, or Flatpak files (amongst others).

```bash
yarn make
```

<br />

## Publish : Production

Publishing is a way of taking the artifacts generated by the `make` command and sending them to a service somewhere for you to distribute or use as updates. (This could be your update server or an S3 bucket)

```bash
yarn publish
```