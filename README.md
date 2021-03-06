Snorlax
=======

The ultimate lazy library. Can cause a thread to sleep for a random amount of
time.


This looks useless, what is this really?
----------------------------------------

Snorlax is a good citizen in the Swift ecosystem. It's a reference
implementation to support as many different platforms as possible.

Snorlax currently supports the following platforms:

- Mac OS X
- iOS
- tvOS
- watchOS
- Linux

Using the following Package Managers:

- [CocoaPods](https://cocoapods.org/)
- [Carthage](https://github.com/Carthage/Carthage)
- [Swift Package Manager](https://swift.org/package-manager/)
- Adding as an Xcode Subproject

Feel free the look at the [commit
history](https://github.com/tryswift/Snorlax/commits/master) or browse the
documentation to see how to create a library:

- [English](Documentation/en-US/)
- [Français](Documentation/fr-FR/)

Can I try installing it?
========================

Sure, use your favorite package manager. Please note the two different versions:

- Odd minor versions (eg - `0.1.0`) require no dependencies. The latest one is `0.1.1`.
- Even minor versions (eg - `0.2.0`) has dependencies. The latest one is
  `0.2.1`. Currently, these dependencies don't support all the platforms
  properly (WIP).

You can see examples at [Snorlax Samples](https://github.com/jeffh/SnorlaxSamples)

CocoaPods
---------

Add Snorlax to your pod file and run `pod install`:

```ruby
# CocoaPods
pod 'Snorlax', '~> 0.1.0'
```

Carthage
--------

Add Snorlax to your `Cartfile` (package dependency) or `Cartfile.private`
(development dependency):

```
github "tryswift/Snorlax" ~> 0.1.0
```

Swift Package Manager
---------------------

Add to your `Package.swift` dependencies:

```swift
import PackageDescription

let package = Package(
    // ... your project details
    dependencies: [
        // As a required dependency
        .Package(url: "ssh://git@github.com/tryswift/Snorlax.git", majorVersion: 0)
    ],
    testDependencies: [
        // As a test dependency
        .Package(url: "ssh://git@github.com/tryswift/Snorlax.git", majorVersion: 0)
    ]
)
```

Manually as an Xcode Subproject
-------------------------------

TODO


Contributions
=============

See
[CONTRIBUTING](https://github.com/tryswift/Snorlax/blob/master/CONTRIBUTING.md).
Documentation improvements and translations are welcomed!

