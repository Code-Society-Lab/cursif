<h1 align="center">Cursif</h1>

Cursif is yet another note-taking application that adds an exciting twist to your productivity. Unlike conventional tools, Cursif empowers you with scriptable notes, allowing you to craft personalized macros for streamlined note automation.

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

## Introduction

Cursif redefines the note-taking experience by allowing users to harness the power of scripting to automate repetitive tasks and create custom workflows. Whether you're a developer, student, or business professional, Cursif empowers you to take control of your notes like never before.

## Features

- Scriptable notes for automating tasks
- Easy-to-use interface for creating and managing notes
- Cross-platform compatibility (officially supports Linux)
- Secure and private note storage
- And much more!

## How to Install
> ⚠️ Cursif officially supports Linux only. Although it should work on Windows and MacOS, it could have unexpected behavior or errors.

### Docker (Recommended)

1. Install [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/).
2. Clone the repository and update the submodule:
   ```bash
   git clone https://.../cursif.git
   git submodule update --init --recursive
   ```
3. Create a `.env` file in the root directory and copy the contents of `.env.example` into it.
4. Run `docker-compose up`.
5. Access the backend at [http://localhost:4000](http://localhost:4000) and the frontend at [http://localhost:3000](http://localhost:3000).

### Manual Installation

1. Install [PostgreSQL](https://www.postgresql.org/download/).
2. Follow the installation instructions for the [frontend](https://github.com/Code-Society-Lab/cursif-web#getting-started) and [backend](https://github.com/Code-Society-Lab/cursif-backend#getting-started).

## Configuration

Before running Cursif, please make sure that you configure any necessary environment variables and settings. 
- Create a new file named `.env` in the root directory.
- Copy the content of `.env.example` into your `.env` 

## Usage

Once installed, start exploring Cursif's features by visiting the [http://localhost:3000](http://localhost:3000) and if needed the [http://localhost:4000](http://localhost:4000) in your browser.
You can try the app by creating a new account or using the dev user with the following credentials:
```
Email   : dev@example.com
Pasword : Password1234
```

## Contributing

We welcome contributions from the community! If you'd like to contribute to Cursif, please review our [contributing guidelines](CONTRIBUTING.md) for more information.

## License

Cursif is licensed under the [GPL 3.0](LICENSE) license. By using this software, you agree to comply with the terms and conditions of this license.

---

Feel free to join our [Discord server](https://discord.gg/code-society-823178343943897088) to connect with other users and contributors!
