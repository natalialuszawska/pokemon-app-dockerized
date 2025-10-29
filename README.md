# 🐳 Pokémon App — Dockerized

This repository provides a fully containerized setup for the **Pokémon App** — consisting of a **Vue 3 + Vite frontend** and a **Node.js + Express backend proxy** to the public [PokeAPI](https://pokeapi.co/).

The goal of this project is to make it possible to launch both services using a single command:
```bash
docker compose up --build

To get updates from submodules:
git submodule update --remote --merge
