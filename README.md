# RxJava2Consumers

Provides a copy of the interfaces that were moved from RxJava 2 into [RxJava2Extensions](https://github.com/akarnokd/RxJava2Extensions#extra-functional-interfaces).

## Usage

The difficulty here is to provide a version of the interfaces that is interchangeable with the RxJava2Extensions ones but do not collide in case both dependencies are declared for the same project. It relies on maven resolution for this.

## Distribution

Add as a dependency to your `build.gradle`
```groovy
repositories {
    ...
    maven { url "https://jitpack.io" }
    ...
}
    
dependencies {
    ...
    compile 'com.github.pakoito:RxJava2Consumers:1.0.0'
    ...
}
```
or to your `pom.xml`

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>

<dependency>
    <groupId>com.github.pakoito</groupId>
    <artifactId>RxJava2Consumers</artifactId>
    <version>1.0.0</version>
</dependency>
```

## License

Copyright (c) pakoito 2017

The Apache Software License, Version 2.0

See LICENSE.md
