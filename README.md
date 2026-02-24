# shared-workflows

## Script Requirements

### deploy-cdk

#### Root package.json

- `build`: This script should build all resources in the repo
- `cdk-deploy`: This script should call `cdk deploy`

### lint-format-check

#### Root package.json

- `build`: This script should build all resources in the repo
- `lint-check`: This script should throw an error if it does not conform to the linting rules
- `format-check`: This script should throw an error if it does not conform to the formatting rules

### publish-sdk-snapshot

#### Root package.json

- `build`: This script should build TS files to JS for publishing

### unit-test

#### Root package.json

- `build`: This script should build all resources in the repo
- `test-coverage`: This script should perform unit tests with a coverage output
