# Deployment

## App

Run locally with `uvicorn src.app.main:app --reload` or build the container with `docker build -t revenue-anomaly-watch .`.

## Landing page

This repository includes a static 3D landing page in `docs/`. It is designed for GitHub Pages publishing at:

`https://r-behera.github.io/revenue-anomaly-watch/`

## CI

A lightweight GitHub Actions workflow checks Python setup and smoke-test structure.
