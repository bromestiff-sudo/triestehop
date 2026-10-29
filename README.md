# Trieste Hop

A 2D platformer set in Trieste, by Kokoro Studio.

This repository is connected to a Cloudflare Worker: every push to `main` republishes the game automatically.
`wrangler.jsonc` serves the files in the repository root as static assets; `.assetsignore` keeps repository-only files private.
