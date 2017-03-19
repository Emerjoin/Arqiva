# Arqiva official-docs project
This is the arqiva's official documentation project.
You can read the online documentation as we write by clicking [here](https://emerjoin.github.io/Arqiva/).

# Motivation to build Arqiva
Arqiva's primary goal was to help us easily produce great documentation for [Hi-Framework](https://github.com/Emerjoin/Hi-Framework). 
We were using [Daux.io](http://daux.io) which was not proving itself to be flexible and awesome enough.
 
# How is Arqiva different from Daux.io
* Its Java based
* Its highly extensible: Arqiva has an architecture inspired by Maven in terms of modularity and allows teams to build personalized documentation
without having to look for another documentation tool. Teams can choose or build their own template engine, they can even pick their preferred markdown
parser with the flavours they love. Arqiva provides hooks to let third-party java code transform the generated HTML in the different phases it observes.
* Its built to work with an awesome built tool: Maven. Adding a new module means nothing but adding a new maven dependency


# Arqiva's source-code repositories
If you are looking for arqiva's source code, you will find below the different repositories where
you will be able to find arqiva's artifacts source-code.


## Arqiva-core
The core of arqiva. Implements the core concepts: project, context, topic files, topic tree, modules (extensibility), hooks.
The source code of this artifact is located at [https://github.com/talk-code/Arqiva-core](https://github.com/talk-code/Arqiva-core).

## Arqiva-web
This artifact provides the infrastructure to render arqiva docs from a java web-container.
The source code of this artifact is located at [https://github.com/talk-code/Arqiva-web](https://github.com/talk-code/Arqiva-web).

## Arqiva-mojo
This artifact consists of the maven plugin used to run and build arqiva projects.
The source code of this artifact is located at [https://github.com/talk-code/Arqiva-mojo](https://github.com/talk-code/Arqiva-mojo).

## Arqiva-basic
This artifact consists of the __arqiva-basic__ module. It's module that integrates [Apache Velocity](http://velocity.apache.org/) and the Java implementation of [CommonMark](https://github.com/atlassian/commonmark-java) by atlassian
into the Arqiva's ecosystem.
The source code of this artifact is located at [https://github.com/talk-code/Arqiva-mojo](https://github.com/talk-code/Arqiva-mojo).


# Arqiva's maven repository
```xml

    <repository>
        <id>Emerjoin</id>
        <name>maven-repo</name>
        <url>https://github.com/Emerjoin/maven-repo/raw/master</url>
   </repository>

```
