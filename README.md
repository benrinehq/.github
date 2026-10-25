# benrinehq/.github

Default community health files for the [benrinehq](https://github.com/benrinehq) organization.

GitHub applies these files to every repository in the organization that does not already define its own copy. This repository has to stay public for those defaults to apply, including to private repositories.

## Pull request templates

| Template | File | Use when |
| --- | --- | --- |
| Feature | [`feature.md`](.github/PULL_REQUEST_TEMPLATE/feature.md) | New functionality |
| Bug fix | [`bugfix.md`](.github/PULL_REQUEST_TEMPLATE/bugfix.md) | A non-urgent defect |
| Hotfix | [`hotfix.md`](.github/PULL_REQUEST_TEMPLATE/hotfix.md) | An urgent production fix |

Choose a template by adding `template` to the compare URL when opening a pull request:

```text
https://github.com/benrinehq/<repo>/compare/<base>...<head>?template=feature.md&expand=1
```

Use `bugfix.md` or `hotfix.md` in place of `feature.md`.

A repository uses its own templates instead of these when it contains `.github/PULL_REQUEST_TEMPLATE.md` or a `.github/PULL_REQUEST_TEMPLATE/` directory.
