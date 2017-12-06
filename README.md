# Zacatzontli

[![Travis](https://img.shields.io/travis/murilocosta/zacatzontli.svg?style=flat-square)](https://travis-ci.org/murilocosta/zacatzontli)
[![GitHub issues](https://img.shields.io/github/issues/murilocosta/zacatzontli.svg?style=flat-square)](https://github.com/murilocosta/zacatzontli/issues)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/04f5303d431d4b5d946413be4c19bafe)](https://www.codacy.com/app/murilocosta/zacatzontli?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=murilocosta/zacatzontli&amp;utm_campaign=Badge_Grade)
[![Codacy Badge](https://api.codacy.com/project/badge/Coverage/04f5303d431d4b5d946413be4c19bafe)](https://www.codacy.com/app/murilocosta/zacatzontli?utm_source=github.com&utm_medium=referral&utm_content=murilocosta/zacatzontli&utm_campaign=Badge_Coverage)

Zacatzontli is an open source lightweight authentication manager API developed with [Node JS](https://nodejs.org).

## Setup

The minimum requirements are:

- [Mongo DB](https://www.mongodb.com) (>= 3.2)
- [Node JS](https://nodejs.org) (~ 6.10.3)

## Installation

To download and build the project, open a terminal and execute:

```
git clone https://github.com/murilocosta/yacatecuhtli.git
cd yacatecuhtli
npm install
```

With this, all dependencies will be installed at `node_modules` directory.

## Configuration

Change the default values at `app/config.js` or set the required environment variables:

```
MONGO_CONNECTION_URL=[mongo_db_connection_url]
JWT_SECRET_KEY=[jwt_secret_key]
BCRYPT_PASSWORD_SALT=[bcrypt_password_salt]
```

## Tests

To execute all tests, open a terminal and execute:

```
npm test
```

## License

Zacatzontli is Copyright © 2017 Murilo Costa.

It is free software, and may be redistributed under the terms specified in the [LICENSE.md](LICENSE.md)
