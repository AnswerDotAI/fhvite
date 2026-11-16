# Release notes

<!-- do not remove -->

## 0.0.8

### New Features

- Add public `vite_headers` to build Vite script and style headers from a manifest with a configurable base, replacing `_mk_scripts` ([#6](https://github.com/AnswerDotAI/fhvite/issues/6))
- Add dev mode to `add_vite` that runs a localhost Vite server with hot module replacement via app lifespan ([#5](https://github.com/AnswerDotAI/fhvite/issues/5))


## 0.0.7

- pybun dep


## 0.0.6

### New Features

- Always run pybun install on build, skip setup/install/build when `run_build`=False, and resolve paths relative to the directory arg ([#4](https://github.com/AnswerDotAI/fhvite/issues/4))


## 0.0.5

### New Features

- Reinstall when bun.lock is newer than `node_modules` ([#3](https://github.com/AnswerDotAI/fhvite/issues/3))


## 0.0.4

### New Features

- Cache Vite build assets without revalidation ([#2](https://github.com/AnswerDotAI/fhvite/issues/2))


## 0.0.3

### New Features

- Add `run_build` kwarg


## 0.0.2

### New Features

- Support for starlette 1.0 ([#1](https://github.com/AnswerDotAI/fhvite/issues/1))


## 0.0.1

- init release
