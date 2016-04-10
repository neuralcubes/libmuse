[![Release](https://jitpack.io/v/neuralcubes/libmuse.svg)](https://jitpack.io/#neuralcubes/libmuse)
# Intro
A maven repo for easy access to libmuse


In order to use this add the following in your gradle:

```gradle
allprojects {
        repositories {
                ...
                maven { url "https://jitpack.io" }
        }
}
```

```gradle
dependencies {
        compile 'com.github.neuralcubes:libmuse:1.3.0'
}
```

or pom file:

```xml
        <repositories>
                <repository>
                    <id>jitpack.io</id>
                    <url>https://jitpack.io</url>
                </repository>
        </repositories>
```

```xml
        <dependency>
            <groupId>com.github.neuralcubes</groupId>
            <artifactId>libmuse</artifactId>
            <version>1.3.0</version>
        </dependency>
```

                                                                                                        
