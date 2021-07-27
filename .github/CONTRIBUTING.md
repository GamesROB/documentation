# Contributing to the GamesROB Documentation
**This file is a work-in-progress, you should follow what's here but not everything is here.
This is a simple contributing guide you need to follow if you want to help us with our documentation. To limit the barrier of entry, we've made a short list of simple do's and don'ts you can read quickly with more details below (detailed explanations are a work-in-progress).

## Do's
- [x] Use our standard styling that follows [these linters](https://github.com/github/super-linter#supported-linters) except for `rust`, `dotenv`, `armttk`, `pwsh`, and `c#` with [these](https://github.com/bigfinfrank/survival/blob/main/.github/workflows/super-linter.yml) settings.
- [x] Use our standard commit-prefixing scheme 

## Don'ts
- [ ] Include anything that breaks our [`CODE_OF_CONDUCT`](https://github.com/GamesROB/documentation/blob/main/CODE_OF_CONDUCT.md), profane language in particular is a big no.

## Styling
You should conform to the styling suggested by our [linters](https://github.com/bigfinfrank/survival/blob/main/.github/workflows/super-linter.yml), we use the slim image of [github/super-linter](https://github.com/github/super-linter). The only repository-specific thing about this action is that we use the arising `main` branch instead of the traditional default `master`.
If you use `main` you can use the workflow in your own repo without any changes. We encourage you to [change your default to `main`](https://docs.github.com/github/administering-a-repository/managing-branches-in-your-repository/changing-the-default-branch) or edit your copy of `super-linter.yml`, just make sure not push this change with any direct commits/PRs as it would break our workflow.

## Commit prefixing
To make it quick and easy to know what a commit is changing just by reading it's name, we use standard commit-prefixes. These are all in the format of `[Prefix] Commit Message`, there is a list of them below:
- `[Actions]` should be prefixed to changes that affect [GitHub Actions Workflows](https://github.com/bigfinfrank/survival/blob/main/.github/workflows)
- `[Meta]` should be prefixed to changes altering things that are in relation to the repository itself but not the project. An example would be a change to this file- it affects the repository but not the project directly.
- `[Wiki]` should be prefixed to changes that affect the [`Wiki/`](https://github.com/bigfinfrank/survival/blob/main/Wiki/) that is added to the GamesROB website.
- `[Misc]` should be prefixed to changes that don't fall under any other prefix.