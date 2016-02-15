# p2plugins

P2 repository available at:

http://maketechnology.github.io/p2plugins

## Add new maven artifacts to pom.xml

Maven artifacts will be converted to OSGi bundles.

See https://github.com/reficio/p2-maven-plugin for details

## Create p2 repo

Run:
```
mvn package
```

## Run local p2 repository

Run:
```
mvn jetty:run
```

## Deploy p2 repository to gh-pages

p2 repository will be available at:
http://maketechnology.github.io/p2plugins

Run:
```
mvn site:site -Dgithub.global.userName=user -Dgithub.global.password=pass
```

