# SimpleGoBLE

Cgo-free Go bindings for SimpleBLE on Windows, macOS, and Linux.

This repository contains the generated Go distribution. Development, tests,
and release automation live in [simpleble/simpleble](https://github.com/simpleble/simpleble/tree/main/simplegoble).

The first packaged Go version has not been published yet. The SimpleBLE CI
will populate this repository with the binding and its prebuilt native libraries.

Versions follow SimpleBLE's `VERSION` file: stable tags are `vX.Y.Z`, and
main-branch development builds use `vX.Y.Z-devN`. Published tags are immutable.

Once published, consumers use `go get github.com/simpleble/simplegoble` and
build normally. Native compilation happens in SimpleBLE CI.
