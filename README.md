# app

Pre-requisites:

- Deployment: Create an account with [Fly.io](https://fly.io/) and install the CLI `brew install flyctl`
- Auth: Create an account with [kinde](https://kinde.com/)
- DB: Create an account with [neon](https://neon.tech/)
- Setup the .env file `cp .env.template .env` and populate the details from Kinde and Neon

To install dependencies:

```bash
bun install && cd frontend/ && bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.0.25. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.
