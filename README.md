# CLibcoro
Libcoro system module package for Swift

## Build
```
swift build
```

## Package.swift
```swift
import PackageDescription

let package = Package(
    name: "MyLibrary",
    dependencies: [
        .Package(url: "https://github.com/noppoMan/CLibcoro.git", majorVersion: 0, minor: 1)
    ]
)
```

## License
CLibcoro is released under the MIT license. See LICENSE for details.
