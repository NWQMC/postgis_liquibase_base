# postgis_liquibase_base

Docker image for use by the IOW team in building databases for use in CI. It is based on postgis-plv8 and contains a JDK and liquibase.

You can build and tag ot locally with:
```
docker build --build-arg LIQUIBASE_VERSION=3.6.3 --build-arg A_JDBC_JAR=postgresql-42.2.5.jar -f Dockerfile -t postgis11-jre11 .
```
