# GA4GH Specification Template [![](https://travis-ci.org/mcupak/ga4gh-specification-template.svg?branch=develop)](https://travis-ci.org/mcupak/ga4gh-specification-template) [![](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://raw.githubusercontent.com/mcupak/ga4gh-specification-template/develop/LICENSE)

This is a [template repository](https://help.github.com/en/articles/creating-a-repository-from-a-template) for setting up repositories containing GA4GH specifications. Use it to [generate new GA4GH repositories](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/).

The repository includes:

- [Minimal OAS 3 specification](openapi.yaml) with a [service-info](https://github.com/ga4gh-discovery/ga4gh-service-info) implementation.
- [Travis CI setup](.travis.yml) validating the OAS 3 specification.
- Core [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) branching setup.
- [Apache 2.0 license file](LICENSE).
- [Common git file exclusions](.gitignore).
- [Common contributing rules](CONTRIBUTING.md).
- [README](README.md) with CI and license badges.