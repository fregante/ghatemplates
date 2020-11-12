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

## [is-dist-up-to-date](./is-dist-up-to-date/is-dist-up-to-date.yml)

If your distribution/built files need to be committed, this workflow will ensure that they are.

This is useful when creating GitHub Actions or simply to verify that files have been formatted (a better `prettier --check`, basically)

```sh
npx ghat fregante/ghatemplates/is-build-committed
```

Requirements:

- A `build` npm script (customizable)
