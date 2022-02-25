# next-auth-server

<h2 align="center">
  The server for study about authentication on Next.JS using Next Auth. Built 
  using Node.js, Express, JWT and Typescript.
</h2>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/areasflavio/next-auth-server.svg">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/areasflavio/next-auth-server.svg">

  <a href="https://github.com/areasflavio/next-auth-server/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/areasflavio/next-auth-server.svg">
  </a>
</p>

<p align="center">
  <a href="#star-features">Features</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#computer-API-Reference">API Reference</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#keyboard-technologies">Technologies</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#computer_mouse-installation">Installation</a>
</p>

# :star: Features

[(Back to top)](#next-auth-server)

This is a server API for study about authentication on Next.JS using Next Auth.
The data are all static just for tests purpose.

Some key features are:

- Token and Refresh Token strategy using JWT.
- Roles and Permissions as auth types.

The application is built using Node.JS with Express framework. The data is not
stored. The entire codebase is written using Typescript.

The frontend can be found in this [repo](https://github.com/areasflavio/next-auth)

> Project developed at Chapter IV of Rocketseat's Ignite bootcamp.

<br/>

# :computer: API-Reference

[(Back to top)](#next-auth-server)

### Login with a user

```http
  POST /session
```

| Body       | Type     | Description                        |
| :--------- | :------- | :--------------------------------- |
| `email`    | `string` | **Required**. Email of the user    |
| `password` | `string` | **Required**. Password of the user |

<br/>

> All next routes need authentication!

<br/>

### Refresh current user token

```http
  POST /refresh
```

| Body           | Type     | Description                             |
| :------------- | :------- | :-------------------------------------- |
| `refreshToken` | `string` | **Required**. Refresh token of the user |

### Get current user info

```http
  GET /me
```

<br/>

# :keyboard: Technologies

[(Back to top)](#next-auth-server)

This is what i used and learned with this project:

- [x] Node.JS
- [x] Express
- [x] JWT
- [x] UUID
- [x] Typescript

<br/>

# :computer_mouse: Installation

[(Back to top)](#next-auth-server)

To use this project, first you need NodeJS running in your device, then you can
follow the commands below:

```bash
# Clone this repository
git clone https://github.com/areasflavio/next-auth-server.git

# Go into the repository
cd next-auth-server

# Install dependencies for the backend
yarn install

# To start the express development server, run the following command
yarn dev
```

# :man_technologist: Author

[(Back to top)](#next-auth-server)

Build by Flávio Arêas 👋 [Get in touch!](https://www.linkedin.com/in/areasflavio/)
