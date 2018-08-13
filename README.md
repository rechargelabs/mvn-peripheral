Maven-Peripheral
================

A non-central maven repository that includes some artifacts that aren't included on Maven Central.

Configure your `build.gradle` like so:

```groovy
repositories {
    mavenCentral()
    maven { url 'https://github.com/rechargelabs/mvn-peripheral/raw/SHA/' }
}
```

`compile` away like you would with any other repo!

```groovy
compile 'com.google.android:annotations:4.1.1.4'
```

# Build steps:

* cd into dagger                                                 
* util/install-local-snapshot.sh
* cp -R ~/.m2/repository/com/google/dagger path/to/mvn-peripheral/com/google/
* cd back into mvn-peripheral                                    
* git commit -m "omg"
* git push
