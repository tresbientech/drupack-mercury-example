# Drupack Mercury example

This repository builds the Mercury Demo site with [Drupack](https://github.com/tresbientech/drupack), through its reusable GitHub workflow.

- `composer.json` and `composer.lock` are the site's Composer project.
- `drupack.yml` names the executable, its Site template and its targets.
- `.github/workflows/build.yml` calls Drupack's `build.yml` at an engine tag. A tag push publishes a release.

Install the latest release into the current directory:

```sh
curl -fsSL https://github.com/tresbientech/drupack-mercury-example/releases/latest/download/install-mercury-demo.sh | sh
```

[Build your site](https://github.com/tresbientech/drupack/blob/main/docs/build-your-site.md) covers the setup.
