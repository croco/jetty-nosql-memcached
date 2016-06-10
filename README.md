# bizid-jvm

## changed

* remove original spy.memcached
* add aws elasticace library

## branch `bizid-jvm-prod`
1. change branch

	git co bizid-jvm-prod

2. build

	mvn clean package

3. get jar

	jetty-nosql-memcached/jetty-nosql-memcached-0.6.0-SNAPSHOT-jar-with-dependencies.jar

4. rename

	cp jetty-nosql-memcached-0.6.0-SNAPSHOT-jar-with-dependencies.jar ~/some/path/jetty-nosql-memcached-0.6.0-SNAPSHOT-jar-with-dependencies-prod.jar

## branch `bizid-jvm-dev`
1. change branch

	git co bizid-jvm-dev

2. build

	mvn clean package

3. get jar

	jetty-nosql-memcached/jetty-nosql-memcached-0.6.0-SNAPSHOT-jar-with-dependencies.jar

4. rename

	cp jetty-nosql-memcached-0.6.0-SNAPSHOT-jar-with-dependencies.jar ~/some/path/jetty-nosql-memcached-0.6.0-SNAPSHOT-jar-with-dependencies-dev.jar
