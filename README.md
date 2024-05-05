<h1 align="center">Cursif</h1>

<div align="center">
  <a href="https://discord.gg/code-society-823178343943897088">
    <img src="https://discordapp.com/api/guilds/823178343943897088/widget.png?style=shield" alt="Join on Discord">
  </a>
  <a href="https://opensource.org/licenses/gpl-3.0">
    <img src="https://img.shields.io/badge/License-GPL%203.0-blue.svg" alt="License">
  </a>
  <a href="https://github.com/code-society-lab/cursif/commits/main">
    <img src="https://img.shields.io/github/last-commit/code-society-lab/cursif.svg" alt="Last Updated">
  </a>
  <a href="https://hexdocs.pm/elixir/Kernel.html">
    <img src="https://img.shields.io/badge/Elixir-1.14.3-4e2a8e" alt="Elixir">
  </a>
  <a href="https://hexdocs.pm/phoenix/overview.html">
    <img src="https://img.shields.io/badge/Phoenix-1.6.15-ff6f61" alt="Phoenix">
  </a>
  <a href="https://www.typescriptlang.org/">
    <img src="https://img.shields.io/badge/TypeScript-5.4.5-blue" alt="TypeScript">
  </a>
  <a href="https://nextjs.org/">
    <img src="https://img.shields.io/badge/Next.JS-13.5.6-black" alt="Next.JS">
  </a>
  <a href="https://www.postgresql.org/">
    <img src="https://img.shields.io/badge/PostgreSQL-15.3-008bb9" alt="PostgreSQL">
  </a>
</div>

Cursif is yet another note-taking application that adds an exciting twist to your productivity. Unlike conventional tools, Cursif empowers you with scriptable notes, allowing you to craft personalized macros for streamlined note automation.

## How to Install

> ⚠️ Cursif officially supports Linux only. Although it should work on Windows and MacOS, it could have unexpected behavior or errors.


Start by pulling the repository and updating the submodules.

```bash
git clone https://.../cursif.git
git submodule update --init --recursive
```

### .env
- In the root directory, create a new file named `.env`.
- Copy the content of `.env.example` into your `.env` 

### Docker (recommended)
You can run the application using Docker and Docker Compose. This is the recommended way to run the application.
Docker will take care of the database, backend, and frontend setup.

- Install [Docker](https://docs.docker.com/get-docker/)
- Install [Docker Compose](https://docs.docker.com/compose/install/)
- Execute `docker-compose up`

You can now access the backend on [`http://localhost:4000`](http://localhost:4000) and the frontend on [`http://localhost:3000`](http://localhost:3000).

### Manual

- Install [Postgresql](https://www.postgresql.org/download/).

- [Frontend](https://github.com/Code-Society-Lab/cursif-web#getting-started).
- [Backend](https://github.com/Code-Society-Lab/cursif-backend#getting-started).
