# p2plugins

http://maketechnology.github.io/p2plugins

## Add new <artifact> to pom.xml

See https://github.com/reficio/p2-maven-plugin for details

## Create p2 repo with

```
$ mvn package
```

## Run local p2 repository

```
$ mvn jetty:run
```

## Deploy p2 repository to http://maketechnology.github.io/p2plugins

```
$ mvn site:site -Dgithub.global.userName=user -Dgithub.global.password=pass
```

