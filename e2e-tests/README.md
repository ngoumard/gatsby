# End to End Tests

These are end to end tests triggered via a CI job. You can run these tests locally by following the [running tests][#running-the-tests], and they're automatically run as part of a CI workflow which runs when packages/_ or the e2e-tests/_ directory is changed in a commit.

## Adding a new e2e test

- Create a folder `e2e-tests/name-of-the-test`
- Copy structure from an existing test, e.g. [`e2e-tests/path-prefix`][./path-prefix]
- Add your tests in `e2e-tests/name-of-the-test/cypress/integration/your-test-here.js`

## Running the Tests

- `cd` to the test (e.g. `cd e2e-tests/gatsby-image`)
- Install dependencies: `yarn` or `npm install`
- OPTIONAL: [use `gatsby-dev` CLI to link current changes in packages/][gatsby-dev-cli]
- Run the `test` script, e.g. `yarn test` or `npm test`

Thanks for contributing to Gatsby! 💜

[gatsby-dev-cli]: https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-dev-cli
