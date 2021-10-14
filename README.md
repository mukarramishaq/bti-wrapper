# Bill the Investor

This is a wrapper app that uses `docker-compose` to run both both backend and frontend containers together.

## Prerequisites

1. Docker
2. Docker Compose

## How to?

In your project directory:

1. Update the git submodules (backend, frontend) using the following command:

```bash
git submodule update --init --recursive
```

2. Run the following command to start the application:

```bash
docker-compose up -d
```

After that you can access the:

1. Backend API at `localhost:11000`
2. Dashabord App at `localhost:5000`
