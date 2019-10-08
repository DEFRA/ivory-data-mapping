# Ivory Shared code

[![Build Status](https://travis-ci.com/DEFRA/ivory-data-mapping.svg?branch=master)](https://travis-ci.com/DEFRA/ivory-data-mapping)
[![Known Vulnerabilities](https://snyk.io/test/github/defra/ivory-data-mapping/badge.svg)](https://snyk.io/test/github/defra/ivory-data-mapping)
[![Code Climate](https://codeclimate.com/github/DEFRA/ivory-data-mapping/badges/gpa.svg)](https://codeclimate.com/github/DEFRA/ivory-data-mapping)
[![Test Coverage](https://codeclimate.com/github/DEFRA/ivory-data-mapping/badges/coverage.svg)](https://codeclimate.com/github/DEFRA/ivory-data-mapping/coverage)

## Development Team

This module was developed by the Ivory team as part of a digital transformation project at [DEFRA](https://www.gov.uk/government/organisations/department-for-environment-food-rural-affairs), a department of the UK government

## Prerequisites

Please make sure the following are installed:

- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Node.js v10/Dubnuim](https://nodejs.org/en/) recommend
  installing nvm and using `nvm install --lts`
- [StandardJS](https://standardjs.com/) using `npm install -g standard`

Check that your environment is running the correct versions of `node` and `npm`:
```bash
$ npm --version
6.9.0
$ node --version
v10.15.3
```

## Installation

Clone the repository and install its package
dependencies:

```bash
git clone https://github.com/DEFRA/ivory-data-mapping.git && cd ivory-data-mapping
npm install
```

## Unit testing the shared code

Use the following **npm** task. This runs the **StandardJS**
linting as well as the unit tests to produce a `coverage.html`
report

```bash
npm test
```

## Contributing to this project

If you have an idea you'd like to contribute please log an issue.

All contributions should be submitted via a pull request.

## License

THIS INFORMATION IS LICENSED UNDER THE CONDITIONS OF THE OPEN
GOVERNMENT LICENCE found at:

<http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3>

The following attribution statement MUST be cited in your products
and applications when using this information.

>Contains public sector information licensed under the Open
>Government license v3

### About the license

The Open Government Licence (OGL) was developed by the Controller
of Her Majesty's Stationery Office (HMSO) to enable information
providers in the public sector to license the use and re-use of
their information under a common open licence.

It is designed to encourage use and re-use of information freely
and flexibly, with only a few conditions.

