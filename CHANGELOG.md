# Changelog

## 0.1.5 (15-03-2019)
- use yaml's safe_load instead of load
- bump swagger ui to 3.21.0
- fixed compatibility with aiohttp>3

## 0.1.4 (31-01-2019)
- ability to set key where validated data stored in request
- bump swagger ui to 3.20.5

## 0.1.3 (14-01-2019)
- fixed forgot to pass named resources for GET methods

## 0.1.2 (27-12-2018)
- added support for application/x-www-form-urlencoded (only primitives)

## 0.1.1 (25-12-2018)
- fixed detection of content-type
- added ability to work with handler decorators
- type annotations are checked in strict mode now
- fixed error when route wasn't in spec file

## 0.1 (22-12-2018)
- first public version