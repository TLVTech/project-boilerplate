<p align="center"><img src="https://user-images.githubusercontent.com/1479215/206780298-2b98221d-9c57-4cd3-866a-cf85ec1ddd9e.jpg" alt="TLVTech README Splash Image" /></p>

# [Project Checklist](https://tlvtech.io/) &middot; [![(Runtime) Build and Test](https://github.com/TLVTech/project-boilerplate/actions/workflows/runtime_build_and_test.yml/badge.svg)](https://github.com/TLVTech/project-boilerplate/actions/workflows/runtime_build_and_test.yml)

Project Checklist
- [ ] CI/CD Set up.
- [ ] [Husky linter connected](https://dev.to/kreshby/keep-your-code-clean-with-eslint-prettier-pre-commit-and-pre-push-hooks-using-husky-lint-staged-and-pretty-quick-4fka)
- [X] All required access (root, etc) is given to systems.
- [ ] .env files are setup and included in the repository.
- [ ] External library versions are pinned.
- [X] All scripts and tools can be found from documentation or version control.
- [ ] Architecture document.
- [ ] Monitoring is set up.
- [ ] Infrastructure-as-code is set up.

## General architecture

![architechture](https://user-images.githubusercontent.com/86567744/161579151-cdb97ccd-157c-440a-9fb2-ffaf4eef6e12.jpeg)

## Local execution

Here's how to run the project locally:

```bash
npm i
npm run start
```

This example will run the backend.

## External tools

* [AWS](https://console.aws.amazon.com/console/home)
* [Expo](https://expo.dev/)
* [Sentry](https://sentry.io/)


## Deployment

Here's how to deploy the project:

```bash
sls deploy
```
