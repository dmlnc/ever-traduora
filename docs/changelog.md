---
id: changelog
title: Changelog
sidebar_label: Changelog
---

To download the source code for each release, check out [GitHub](https://github.com/ever-co/ever-traduora/releases). Alternatively docker images are available for each release on [Docker Hub](https://cloud.docker.com/u/everco/repository/docker/everco/ever-traduora).

## next

- TODO

## 0.19.4

- Multiple packages updates and tiny fixes
- [PR-339:](https://github.com/ever-co/ever-traduora/pull/339) Add fallback locale on export (thanks @kidoncio)
- [PR-340:](https://github.com/ever-co/ever-traduora/pull/340) Add Context on Term (thanks @kidoncio)
- [PR-310:](https://github.com/ever-co/ever-traduora/pull/310) Make the DB type as variable (thanks @azlux)

## 0.19.3

- We fixed all e2e and Unit tests in this release :rocket:
- [PR-296:](https://github.com/ever-co/ever-traduora/pull/296) Fix e2e testing
- [PR-295:](https://github.com/ever-co/ever-traduora/pull/295) More CSV Injection related tests
- [PR-294:](https://github.com/ever-co/ever-traduora/pull/294) and [PR-293:](https://github.com/ever-co/ever-traduora/pull/293) Fix some Unit Tests

## 0.19.2

- [PR-289:](https://github.com/ever-co/ever-traduora/pull/289) CSV Injection Vulnerability Fixes
- some minor packages updates (mostly for security)
- fix CircleCI builds and split e2e and unit tests running

## 0.19.1

- [PR-216:](https://github.com/ever-co/ever-traduora/pull/253) Update Angular / NestJs and other packages to latest

## 0.19.0

- [Commit](https://github.com/ever-co/ever-traduora/commit/7173276f9c049f4a8db7e7bf47fa27667421ab2c) Docker / Docker Compose improvements
- [PR-222:](https://github.com/ever-co/ever-traduora/pull/222) Support for Resource ResX files added (thanks @rai69)
- [PR-202:](https://github.com/ever-co/ever-traduora/pull/202) Add support for Docker Secrets (thanks @ynuyasha)

## 0.18.0

- [PR-216:](https://github.com/ever-co/ever-traduora/pull/216) Update Angular / NestJs and other packages to latest
- [PR-173:](https://github.com/ever-co/ever-traduora/pull/173) Security Fix for Username Enumeration (thanks @JamieSlome / @huntr-helper)

## 0.17.0

- [PR-91:](https://github.com/ever-co/ever-traduora/pull/91) Add support for PHP import/export format.
- [PR-153:](https://github.com/ever-co/ever-traduora/pull/153) Add option to debug emails locally
- [PR-122:](https://github.com/ever-co/ever-traduora/pull/122) Upgraded to Angular 9+.
- [PR-154:](https://github.com/ever-co/ever-traduora/pull/154) Add option to reject self-signed certs from mail server.
- Upgrade Docker images to Node 12.18.
- Upgraded dependencies.
- Minor performance improvements and bug-fixes.

## 0.16.0

- Allow config of max nested levels on import formats (with new default of 100).
- Pretty print JSON based exporters.

## 0.15.1

- Fix parsing of gettext (po) files with message contexts.

## 0.15.0

- [PR-72](https://github.com/ever-co/ever-traduora/pull/72) You can now organize your terms and translations with labels.
- [PR-89:](https://github.com/ever-co/ever-traduora/pull/89) Added translation progress stats per locale.
- [PR-94](https://github.com/ever-co/ever-traduora/pull/94) Fix escaping of special characters on Android Resources.
- Automatically detect file import format.
- Increase max size for file import (1MB).
- Improve error message when importing files which are too large.

## 0.14.0

- Minor bug fixes and UI improvements.
- Changed DB tables collation to support case-sensitive terms.
- [PR-87:](https://github.com/ever-co/ever-traduora/pull/87) We now support the Android Resources (XML) format.

## 0.13.0

- [PR-66:](https://github.com/ever-co/ever-traduora/pull/66) You can now invite non-traduora users into your project with the new invite system.
- Updated API reference docs.

## 0.12.1

- Ensure swagger version is same as in package.json
- expose version in `/health` endpoint

## 0.12.0

- You can now sign-in with Google.
- Fix search component case sensitivity.
- Various dependency upgrades and security fixes.

## 0.11.0

- Add swagger API docs
- Conform auth token endpoint to oauth2 conventions

## 0.10.0

- Support Apple .strings format
- Set default MySQL charset to utf8mb4. You can now use emojis in terms and translations
- Use lexical order for terms on export and find all endpoint

## 0.9.0

- Added support to import and export Gettext (po) files
- Change default encoding for Java properties format to ISO-8859-1
- Add guard against account deletion when is last project admin of project with team
- Upgrade webapp dependencies
- Minor improvements and bug fixes

## 0.8.7

- Initial open source release
