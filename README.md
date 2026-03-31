# WooriDo Meta Repository

This repository is the root meta repository for WooriDo.

## Structure

- `docs/`: project documentation
- `backend/`: submodule -> `https://github.com/wooridoo/backend.git`
- `frontend/`: submodule -> `https://github.com/wooridoo/frontend.git`

## Branch Policy

- Primary branch: `main`

## Clone and Initialize

```bash
git clone <this-repo-url>
cd woorido
git submodule sync --recursive
git submodule update --init --recursive
```

## Existing Clone Update

```bash
git pull --ff-only origin main
git submodule sync --recursive
git submodule update --init --recursive
```

