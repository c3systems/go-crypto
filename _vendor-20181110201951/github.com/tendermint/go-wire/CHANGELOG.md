# Changelog

## 0.7.0 (Oct 26, 2017)

BREAKING CHANGE:
 - time: panic on encode, error on decode for times before 1970
 - rm codec.go

IMPROVEMENTS:
 - various additional comments, guards, and checks

BUG FIXES:
 - fix default encoding of time and bytes
 - don't panic on ReadTime
 - limit the amount of memory that can be allocated

## 0.6.2 (May 18, 2017)

FEATURES:

- `github.com/tendermint/go-data` -> `github.com/tendermint/go-wire/data`

IMPROVEMENTS:

- Update imports for new `tmlibs` repository

## 0.6.1 (April 18, 2017)

FEATURES:

- Size functions: ByteSliceSize, UvarintSize
- CLI tool 
- Expression DSL
- New functions for bools: ReadBool, WriteBool, GetBool, PutBool
- ReadJSONBytes function


IMPROVEMENTS:

- Makefile
- Use arrays instead of slices
- More testing
- Allow omitempty to work on non-comparable types

BUG FIXES:

- Allow time parsing for seconds, milliseconds, and microseconds
- Stop overflows in ReadBinaryBytes


## 0.6.0 (January 18, 2016)

BREAKING CHANGES:

FEATURES:

IMPROVEMENTS:

BUG FIXES:


## Prehistory
