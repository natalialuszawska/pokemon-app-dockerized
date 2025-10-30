# 🐳 Pokémon App — Dockerized

This repository provides a fully containerized setup for the **Pokémon App** — consisting of a **Vue 3 + Vite frontend** and a **Node.js + Express backend proxy** to the public [PokeAPI](https://pokeapi.co/).

To run project:
git submodule update --init --recursive;
docker compose up --build

To get updates from submodules:
git submodule update --remote --merge
