# Web Auth III Guided Project

Guided project for **Web Auth III** Module.

## Prerequisites

- [SQLite Studio](https://sqlitestudio.pl/index.rvt?act=download) installed.

## Project Setup

- [ ] fork and clone this repository.
- [ ] **CD into the folder** where you cloned **your fork**.
- [ ] type `yarn` or `npm i` to download dependencies.
- [ ] type `yarn server` or `npm run server` to start the API.

Please follow along as the instructor adds support for `JSON Web Tokens (JWT)` to the API.

## Responsibilities of the server and client

### Server

- generate the token
- send the token to the client
- read, decode, and verify the token
- make the payload available for the api

### Client

- store the token
- send the token on every request
