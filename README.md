# postgis_liquibase_base


docker build  -f Dockerfile -t usgswma/postgis-plv8:10-2.1.2 .


docker build --build-arg LIQUIBASE_VERSION=3.6.3 --build-arg A_JDBC_JAR=postgresql-42.2.5.jar -f Dockerfile -t postgis10-jre11 .

