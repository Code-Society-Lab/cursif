# Cursif
Cursif is yet another note-taking application that adds an exciting twist to your productivity. Unlike conventional tools, Cursif empowers you with scriptable notes, allowing you to craft personalized macros for streamlined note automation.

## How to Install

> ⚠️ Cursif officially supports Linux only. Although it should work on Windows and MacOS, it could have unexpected behavior or errors.


Start by pulling the repository and update the submodules.

```bash
git clone https://.../cursif.git
git submodule update --init --recursive
```

### Docker (recommended)

- Install [Docker](https://docs.docker.com/get-docker/)
- Install [Docker Compose](https://docs.docker.com/compose/install/)
- Execute `docker compose up`

You can now access the backend on [`http://localhost:4000`](http://localhost:4000) and the frontend on [`http://localhost:8080`](http://localhost:8080).

### Manual

- Install [Postgresql](https://www.postgresql.org/download/).

- [Frontend](https://github.com/Code-Society-Lab/cursif-backend#getting-started).
- [Backend](https://github.com/Code-Society-Lab/cursif-frontend#getting-started).