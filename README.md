# springboot-liquibase
Sample project for spring-boot | postgresql | liquibase | liquibase-maven-plugin integration

It generates liquibase table and runs the initial changesets defined in `0.1-release-initial.xml`

You can generate differences as changeset between two databases by configuring the app in `liquibase.properties` file
and running the `mvn liquibase:diff` command. This will generate a diff file -which contains a set of changes- named as 
`liquibase-diff-changeLog.xml`.
