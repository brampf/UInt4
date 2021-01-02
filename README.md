#  UInt4 
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

UInt4 is a Swift library that represents a 4-bit unsigned data type.

## About
`UInt4` conforms to the same protocols as built-in unsigned integer type (eg. `UInt8`, `UInt16`, etc).  This means that `UInt4` can be worked with as any other `UIntX` provided by the standard library.

The minimum value that can be represented in a `UInt4` is `0`.
The maximum value that can be represented in a `UInt4` is `15`.

The `UInt4` library has a comprehensive test suite.

Internally, the bits of the `UInt4` are represented in an `Int`.  This means that 64-bits of memory (or 32-bits on 32-bit systems) are used for each `UInt4`.

## Getting started

### Swift Package Manager

With the swift package manager, add the library to your dependencies
```swift
dependencies: [
.package(url: "https://github.com/brampf/uint4.git", from: "1.0.0")
]
```

then simply add the `UInt4` import to your target

```swift
.target(name: "YourApp", dependencies: ["UInt4"])
```


Use as any other unsigned integer type in Swift.

## Licence
This project is licensed under the MIT license.  See the [LICENCE](LICENSE) file for more info.
