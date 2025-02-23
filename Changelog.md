# 0.3.0 - 01/03/2020

## Added

- `.reduce()` function to StormDB.

# 0.2.0 - 25/02/2020

## Added

- Typescript types declaration file.
- `.map()` function to StormDB to map values in an array.
- `.filter()` function to StormDB to filter an array.
- `.sort()` function to StormDB to sort an array.

## Changed

- StormDB must be instantiated using the `new` keyword.
- The promise returned by an async-enabled local file engine now rejects if `fs.writeFile` fails.

## Fixed

- Fixed a bug when using non-strings as property key with `.set()`.

# 0.1.1 - 20/02/2020

### Added

- NPM keywords.

### Changed

- Improved Readme - added more documentation and improved badges.

### Fixed

- Inaccurate changelog information.

# 0.1.0 - 20/02/2020

- 🎉 Initial Release of StormDB.
