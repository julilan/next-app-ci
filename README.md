# Next.js App

The purpose of this repo is to practice setting up a relevant Github Actions workflow and containerizing the application.

## Getting started

### Option 1: Run development server

```bash
npm run dev
```

### Option 2: Run as containerized application

```bash
docker compose up
```

Add new dependencies with

```bash
docker-compose run --rm app npm install <package name>
```

In both cases open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
