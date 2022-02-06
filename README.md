# react-esbuild-typescript

Starter template for a React application using Typescript and bundled with esbuild.

## Using the template

```
gh repo create --template chasestubblefield/react-esbuild-typescript
```

## Install dependencies

`node` is required to use `npm`. Installing with Homebrew is sufficient.

```
npm install
```

## Start development server

Serves files from the `dist/` directory while watching and re-compiling JS.

```
npm run start
```

## Build application

Compiles JS into the `dist/js` directory

```
npm run build
```

## Typescript type-checking

While `tsc` is not used for transpilation, type checking can be performed with

```
npm run check
```
