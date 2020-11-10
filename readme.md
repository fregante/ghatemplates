# GH Actions Templates

Use [ghat](https://github.com/fregante/ghat) to easily share your workflows or copy the workflows shared in this repository.

## [webext/release.yml](./webext/release.yml)

```sh
npx ghat fregante/ghatemplates/webext/release.yml
```

And then remember to choose a random `cronjob` value.

Used by:

- https://github.com/sindresorhus/refined-github
- https://github.com/npmhub/npmhub

## [esm-lint](./esm-lint/esm-lint.yml)

Package/ESM compatibility linter, details in https://github.com/sindresorhus/project-ideas/issues/116

```sh
npx ghat fregante/ghatemplates/esm-lint
```

## [node](./node)

Common Node workflows. You can install them all at once with

```sh
npx ghat fregante/ghatemplates/node
```

### [node/xo.yml](./node/xo.yml)

```sh
npx ghat fregante/ghatemplates/node/xo.yml
```

### [node/ava.yml](./node/ava.yml)

```sh
npx ghat fregante/ghatemplates/node/ava.yml
```

### [node/build.yml](./node/build.yml)

```sh
npx ghat fregante/ghatemplates/node/build.yml
```
