# Forgelin
Fork of [Emberwalker's Forgelin](https://github.com/Emberwalker/Forgelin).

## Additions
- Shades the Kotlin standard library, runtime, coroutines-core, serialization and reflect libraries, so you don't have to.
- Provides a Forge `ILanguageAdapter` for using Kotlin `object` classes as your main mod class.

## Usage

```groovy
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    implementation 'com.github.juraj-hrivnak:Forgelin:master-SNAPSHOT'
}
```

All versions can be seen [here](https://jitpack.io/#juraj-hrivnak/Forgelin).

