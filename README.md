# Sodium - System Module Package for SwiftPM

## Installation
In order to add Sodium as a dependency, you must first create a Swift package. Then in the newly created Package.swift, open it and add Sodium as a dependency

```swift
import PackageDescription

let package = Package(
    name: "yourswiftexecutablehere",
    dependencies: [
        .Package(url: "https://github.com/Azoy/Sodium", majorVersion: 1)
    ]
)
```

## Documentation
Documentation can be found here: https://download.libsodium.org/doc/
