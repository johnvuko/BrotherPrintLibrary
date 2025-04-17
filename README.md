# BrotherPrintLibrary

This repository provides the Brother SDK packaged as a reusable `.aar` file, ready to be integrated into any Android project.

More information here:
[https://support.brother.com/g/s/es/htmldoc/mobilesdk/index.html](https://support.brother.com/g/s/es/htmldoc/mobilesdk/index.html)
[https://www.brother.co.jp/eng/dev/mobilesdk/ios/index.aspx](https://www.brother.co.jp/eng/dev/mobilesdk/ios/index.aspx)

## Installation

### 1. Add JitPack to your `settings.gradle` (project-level)

```groovy
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
```

2. Add the dependency to your app-level `build.gradle`

```groovy
dependencies {
    implementation 'com.github.johnvuko:BrotherPrintLibrary:4.12.0'
}
```

## Author

- [Jonathan VUKOVICH](https://github.com/johnvuko) ([@johnvuko](https://twitter.com/johnvuko))

## License

BrotherPrintLibrary is available under the MIT license. See the LICENSE file for more info.
