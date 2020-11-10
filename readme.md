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

You can also exclude some tests irrelevant to your project:

```sh
npx ghat fregante/ghatemplates/esm-lint --exclude jobs.TypeScript --exclude jobs.Node
```


## [node](./node/ci.yml)

Common Node workflows. You can install them all at once with

```sh
npx ghat fregante/ghatemplates/node
```

or exclude some

```sh
npx ghat fregante/ghatemplates/node --exclude jobs.Test --exclude jobs.Build
```
