# Plans: common prettier config, dockerization, tailwind, ci/cd ideas, modularization and file structure, common ui module and usage etc.

# TODO turbo.json, building, native code

<p align="center">
   <br/>
   <a href="https://github.com/SGeri/turbo-web-ts" target="_blank"><img width="200px" src="https://raw.githubusercontent.com/SGeri/turbo-web-ts/main/turbo-web-preview.png" /></a>
   <h2 align="center">Turbo Web Typescript</h2>
   <p align="center">
   My go-to boilerplate template for fullstack projects built with NextJS, NestJS & Expo.
   </p>
   <p align="center" style="align: center;">
      <a href="https://github.com/SGeri/turbo-web-ts">
        <img alt="stars" src="https://img.shields.io/github/stars/SGeri/turbo-web-ts?style=for-the-badge">
      </a>
      <a href="https://github.com/SGeri/turbo-web-ts">
        <img src="https://img.shields.io/badge/version-1.0.0-<COLOR>?style=for-the-badge" alt="Version"/>
      </a>
      <a href="https://github.com/SGeri/turbo-web-ts">
        <img src="https://img.shields.io/badge/node-16+-blue?style=for-the-badge" alt="Node" />
      </a>
      <a href="https://github.com/SGeri/turbo-web-ts">
        <img src="https://img.shields.io/github/license/SGeri/forrodrot?style=for-the-badge" alt="ISC" />
      </a>
   </p>
</p>

## Overview

The main goal of this project is to provide a boilerplate template for fullstack projects built with NextJS, NestJS & Expo. The project is currently still in development, but it is already usable. I am working on implementing my most used libraries and frameworks into this template, so it can be used for rapid
prototyping and development of new projects.

### Tech Stack

- [NextJS](https://nextjs.org) - React-based server-side rendering framework with advanced routing and built-in TypeScript support
  - [Zustand](https://zustand-demo.pmnd.rs) - Simple state management library with first-class React Hooks support [WIP]
  - [Tailwind](https://tailwindcss.com) - Utility-first CSS framework [WIP]
  - [Mantine](https://mantine.dev) - React UI Framework [WIP]
- [NestJS](https://nestjs.com) - NodeJS backend framework for building efficient, scalable and enterprise-grade server-side applications
  - [Prisma](https://www.prisma.io) - ORM for working with TypeScript [WIP]
- [Expo](https://expo.io) - React Native framework for building native iOS and Android apps
  - [Expo Router](https://expo.github.io/router/docs) - Next-like routing for Expo apps [WIP]
- [Turborepo](https://turbo.build/repo) - Monorepo tooling for rapid development & deployment

## Features

- Common, unified Prettier configuration [WIP]
- Common, unified ESLint configuration [WIP]
- UI package with common components for Next & Expo [WIP]
- Tailwind Support [WIP]
- Authentication boilerplate with Nest [WIP]
- GraphQL [WIP]

## Getting Started

- Next runs on local

### 0. Prerequisites

- [NodeJS 16+](https://nodejs.org/en/download/)

### 1. Clone repository & install dependencies

```
git clone https://github.com/SGeri/turbo-web-ts.git
cd turbo-web-ts
npm install
```

### 2. [...to be continued]

### 3. Run the project in development mode

For local development use the following command:

```
npm run dev
```

## License

ISC
