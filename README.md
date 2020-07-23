# My Library Test

A repository for a simple test custom component library in android

This library is being distributed using JitPack

## How To Add This Library To Your Project

- Step 1
Add it in your root build.gradle at the end of repositories:
```
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```

- Step 2
Add the dependency:
```
dependencies {
  implementation 'com.github.thearthurdev:my_library_test:0.0.1'
}
```
