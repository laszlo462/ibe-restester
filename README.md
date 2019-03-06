# IBE-RESTester

[![Tagged Release](https://img.shields.io/badge/release-v0.1.0-blue.svg?longCache=true)](CHANGELOG.md)
[![Development Status](https://img.shields.io/badge/status-alpha-yellow.svg?longCache=true)](ROADMAP.md)
[![Build Status](https://img.shields.io/badge/build-unknown-lightgrey.svg?longCache=true)](https://travis-ci.org)
[![Build Status](https://img.shields.io/badge/build-pending-lightgrey.svg?longCache=true)](https://www.appveyor.com)
[![Build Coverage](https://img.shields.io/badge/coverage-0%25-lightgrey.svg?longCache=true)](https://codecov.io)

> A simple RESTful API testing utility specific to IBE implementations.

The IBE-RESTester project aims to facilitate easy testing of DLL to IBE participant queries, as well as aid in identifying necessary lookup table changes related to FHIR bundle creation.

## Table of Contents

- [IBE-RESTester](#ibe-restester)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Requirements](#requirements)
  - [Usage](#usage)
  - [Development](#development)
    - [Future](#future)
    - [History](#history)
    - [Community](#community)
  - [Credits](#credits)
  - [License](#license)

## Features

- Simple verification of the DynaLync participant queries of the IBE database.
- Query against a patient MRN, EnterpriseID, Name, or Date of Birth.

## Requirements

Currently the only requirement is Python3.

## Usage

Ensure Python 3.x is installed via `python -V`

Open command prompt to ./src directory and execute the script via `python ibequery.py`.

Input the IP Address of the IBE, then the Participant MRN as prompted. The JSON response from IBE will be displayed.

## Development

See [CONTRIBUTING](CONTRIBUTING.md)

### Future

See [ROADMAP](ROADMAP.md)

### History

See [CHANGELOG](CHANGELOG.md)

### Community

See [CODE OF CONDUCT](CODE_OF_CONDUCT.md)

## Credits

See [AUTHORS](AUTHORS.md)

## License

See [LICENSE](LICENSE)
