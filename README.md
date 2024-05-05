# Cursif
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
