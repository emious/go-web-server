# Go Web Server

A minimal Go web server example that serves static files and handles simple HTTP routes.

## Features

- Serves files from the `static/` directory
- Handles a `/hello` GET route
- Handles a `/form` POST route and prints submitted `name` and `address`

## Prerequisites

- Go 1.25 or later
- Git (optional)

## Run locally

```bash
cd "d:/golang projects/go-web-server"
go run main.go
```

Open `http://localhost:8080` in your browser.

## Endpoints

- `GET /hello` — returns `Hello, World!`
- `POST /form` — accepts form fields `name` and `address`
- `/` — serves static files from the `static/` folder

## Project structure

- `main.go` — entry point and HTTP route handlers
- `go.mod` — Go module definition
- `static/` — optional static assets served by the file server

## Notes

The server prints `Server is listening on http://localhost:8080` and listens on port `8080`. If you want to add front-end assets, place them under `static/`.
