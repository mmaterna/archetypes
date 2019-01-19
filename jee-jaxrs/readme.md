1. Install archetype to local repository
----------------------------------------

In archetype directory:

```
mvn clean install
```


2. Create project from archetype
--------------------------------

In new project directory:

```
mvn archetype:generate -DarchetypeGroupId=pl.mmaterna.archetype -DarchetypeArtifactId=jee-jaxrs -DarchetypeVersion=1.0
```

