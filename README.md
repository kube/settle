![https://github.com/kube/monolite/actions?query=workflow%3ABuild+branch%3Amaster](https://github.com/kube/monolite/workflows/Build/badge.svg)

<h1 align="center">
  <img alt"Monolite"
    src="https://rawgithub.com/kube/monolite/master/logo.svg">
</h1>

<h3 align="center">Type-safe structural-sharing tree modifier.</h3>

<p align="center">
  <img width=670 src="https://user-images.githubusercontent.com/2991143/49388567-7e05e900-f724-11e8-82fd-1e19c53baaea.gif" />
</p>

## Install

```sh
yarn add monolite
```

## TypeScript

The main motivation of this library is to preserve static-typing, type-inference and completion provided by TypeScript, which is not supported by Immutable.js when working on trees.

**Monolite** takes **Plain-Old JavaScript Objects** and returns **Plain-Old JavaScript Objects**. Accessors permit TypeScript to understand the types you're dealing with and to provide completion and linting as if you were working directly on these objects.
