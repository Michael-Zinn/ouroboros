# Ouroboros

![ouroboros logo](Ouroboros-simple.png)

Macro code generator for Java written with Ravr which was generated with Ouroboros, hence the name/logo.

_v0.0.1 (experimental, incomplete)_

## Adding it to your project

### Maven

It's not on Maven Central yet, but you can [find it in JCenter](https://bintray.com/rednifre/ouroboros/ouroboros). First, add JCenter to the repositories in your pom:

```xml
    <repositories>
        <repository>
            <id>jcenter</id>
            <url>http://jcenter.bintray.com </url>
        </repository>
    </repositories>
```

Then you can import it as usual:

```xml
    <dependencies>
        <dependency>
            <groupId>de.michaelzinn.ouroboros</groupId>
            <artifactId>ouroboros</artifactId>
            <version>0.0.1</version>
        </dependency>
    </dependencies>
```

### Gradle

```gradle
compile 'de.michaelzinn.ouroboros:ouroboros:0.0.1'
```

