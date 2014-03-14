# ftp4j

this is fork from http://www.sauronsoftware.it/projects/ftp4j/.

I fix some bugs, and i am hosing this artifact to [my repository](https://github.com/bastengao/mvn-repository).

* fix: MLSD modify time format SHA: c57edf613658ab1b957db03ef5db665e6a2d54cd

add dependency to your project.

```xml
<repositories>
    <repository>
    <id>bastengao-mvn-repository</id>
    <url>https://raw.github.com/bastengao/mvn-repository/master/releases</url>
    </repository>
</repositories>


<dependency>
    <groupId>it.sauronsoftware.ftp4j</groupId>
    <artifactId>ftp4j</artifactId>
    <version>1.7.2-fixed</version>
</dependency>
```

