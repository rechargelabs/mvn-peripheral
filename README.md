Maven-[Peripheral](http://thesaurus.com/browse/central)
================

A non-central maven repository that includes some artifacts that aren't included on Maven Central.

Configure your `build.gradle` like so:

```groovy
repositories {
    mavenCentral()
    maven { url 'https://github.com/ronshapiro/mvn-peripheral/raw/master/' }
}
```

`compile` away like you would with any other repo!

```groovy
compile 'com.google.android:annotations:4.1.1.4'
```