# maven archetype for scala project

* scala 2.11.5 project using maven

## To generate simple hello world scala project

* At first, clone this project.
* cd scala-maven-archetype
* install archetype to local repository by invoke

    	mvn install
* mvn generate using below command

		mvn -DarchetypeCatalog=local archetype:generate -DarchetypeGroupId=starblood.archetypes -DarchetypeArtifactId=maven-scala-archetype -DarchetypeVersion=1.0.0-SNAPSHOT -DgroupId=<groupdId> -DartifactId=<artifactId>


