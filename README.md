# Specification Pattern

[![Build Status](https://travis-ci.org/uetoyo/specification-pattern.svg?branch=master)](https://travis-ci.org/uetoyo/specification-pattern)
[![Release](https://jitpack.io/v/uetoyo/specification-pattern.svg)](https://jitpack.io/#uetoyo/specification-pattern)

The specification pattern as described by *Eric Evans* and *Martin Fowler*.

## Users

It is used in production at Czech Radio together with our repository classes, see the *[Repository Pattern](https://martinfowler.com/eaaCatalog/repository.html)*.

## Getting Started

### Instalation

The installation of the package is possible via [JitPack](https://jitpack.io/#uetoyo/specification-pattern). To add a dependency on Specification latest release using Maven, use the following:

**Step 1**. Add the repository to your build file

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```

**Step 2.** Add the latest release dependency

```xml
<dependency>
    <groupId>com.github.uetoyo</groupId>
    <artifactId>specification</artifactId>
    <version>v0.5.0</version>
</dependency>

```

For another build system check the link above.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/uetoyo/spec/tags). 

## Authors

See also the list of [contributors](https://github.com/uetoyo/specification-pattern/contributors) who participated on this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Overviev of the pattern

### Composite Specification

#### Nullary Composite Specification

In the original paper<sup id="a1">[1](#f1)</sup> it is called the *Leaf Specification*.

#### Unary Composite Specification

#### Binary Composite Specification

#### Multiary Composite Specification

## References

<b id="f1">1</b> https://www.martinfowler.com/apsupp/spec.pdf [↩](#a1)
