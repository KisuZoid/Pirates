# Develop Pirates

We are pleased that you are thinking about contributing to Pirates! This guide details how to contribute to Pirates in a way that is efficient and fun for everyone.

## Branching model

The main development branch for upcoming releases is `master`.
If in doubt, create your pull request against `master`.
All new features, gem updates and bugfixes for the upcoming release should go into the `master` branch.

## Development flow

For contributing source code, please follow the git workflow below:

- **Fork** Pirates on GitHub
- Clone your fork to your development machine:

```
git clone git@github.com/<username>/pirates
```

## Testing

Please add tests to your code to verify functionality, especially if it is a new feature.

Pull requests will be verified by GitHub Actions as well,
but please run them locally as well and make sure they are green before creating your pull request.
Just in case, for a lot of pull requests coming in and it takes some time to run the complete suite for each one.

Please also use `[ci skip]` in your commit message to suppress builds which are not necessary
(e.g. after fixing a typo in the `README`).


## Bugs and fixes

Bugfixes for one of the actively supported versions of Happen should be issued against the respective branch.
Let a fix for the current version (called "fix" and the branch ideally being named `fix/XYZ`)
should target `release/*` and a fix for the former version
(called "back" and the branch ideally being named `back/XYZ`)
should target `back/*`. We will try to merge fixes into main branch
but if that is a non-trivial task, we might ask you to create another PR for that.

## Inactive pull requests

We want to keep the Pull request list as tidy as possible - we will aim close pull requests
after an **inactivity period of 30 days** (no comments, no further pushes)
which are not labelled as `work in progress` by us.

## Security

If you notice a security issue in Pirates, please send us a email to kisuzoid@gmail.com and describe the issue you found.

Please include a description on how to reproduce the issue if possible. Our team will get your email and will attempt to reproduce and fix the issue as soon as possible.
