# CHANGE LOG

All notable changes to the eslint-config-default project.

Copyright 2015, 2016 Sudaraka Wijesinghe <sudaraka@sudaraka.org>

This program comes with ABSOLUTELY NO WARRANTY;
This is free software, and you are welcome to redistribute it and/or modify it
under the terms of the BSD 2-clause License. See the LICENSE file for more
details.

---

## [0.3.1] - 2016-02-11
### Changed
- Make linebreaks to be in before operators (changed my mind).
- Relaxed the requirement of parenthesis around function arguments.
- Turned off id-length rule as it became impractical to maintain exceptions.
- Converted .js files to 2 space indentation.

## [0.3.0] - 2016-01-14
### Changed
- Disabled no-mixed-requires rule in favour of one-var
- Update copyright year to include 2016.
- Disabled padded-block rule as both options given by it makes the code ugly.
- Allow more nested callbacks, need them when using `mocha` testing scripts.
- Switched to using 2 space indentation for JS code.
- Allow _ as short identifier, used to indicate unused variable.
- Allow x and y as short identifiers, used when specifying coordinates.
- Make space after/before object curly braces mandatory.

## [0.2.1] - 2015-11-30
### Added
- Extended configuration file for ES5 projects that target web browsers.

### Changed
- Fixed a typo in package.json author information caused by bad .npmrc setting.

## [0.2.0] - 2015-09-29
### Changed
- Package name changed to `@sudaraka/eslint-config-default`

## [0.1.2] - 2015-09-29
### Deprecated
- Abandoning package name `@sudaraka/eslint-config` to enable better
  extensibility.

## [0.1.1] - 2015-09-28
### Changed
- Allow number id identifier names

## [0.1.0] - 2015-09-28
### Added
- Default ESLint configuration with (almost) all rules enabled
- Scoped npm package to be used by eslint `extends` configuration
- README, LICENSE and CHANGELOG
