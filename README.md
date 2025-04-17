[![](https://jitpack.io/v/johnvuko/BrotherPrintLibrary.svg)](https://jitpack.io/#johnvuko/BrotherPrintLibrary)

# BrotherPrintLibrary

This repository provides the Brother SDK packaged as a reusable `.aar` file, ready to be integrated into any Android project.

More information here:  
[https://support.brother.com/g/s/es/htmldoc/mobilesdk/index.html](https://support.brother.com/g/s/es/htmldoc/mobilesdk/index.html)
[https://support.brother.com/g/s/es/dev/en/mobilesdk/android/index.html](https://support.brother.com/g/s/es/dev/en/mobilesdk/android/index.html)

## Installation

### 1. Add JitPack to your `settings.gradle` (project-level)

```
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
```

2. Add the dependency to your app-level `build.gradle`

```
dependencies {
    implementation 'com.github.johnvuko:BrotherPrintLibrary:4.12.6'
}
```

## Author

- [Jonathan VUKOVICH](https://github.com/johnvuko) ([@johnvuko](https://twitter.com/johnvuko))

## License

BrotherPrintLibrary is available under the MIT license. See the LICENSE file for more info.
