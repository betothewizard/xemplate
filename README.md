# xemplate

a pre-configured monorepo running on vite+. you code, it works.

- `apps/web` - the frontend
- `packages/utils` - shared typescript package

## setup

install dependencies:

```bash
vp i
```

spin up the dev server:

```bash
vp run dev
```

## pipeline

check formatting, lint, and run tests:

```bash
vp run ready
```

manually run tests:

```bash
vp run -r test
```

build the monorepo:

```bash
vp run -r build
```
