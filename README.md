maven
=====

CloudMine Public Maven Repository

https://cloudminellc.atlassian.net/wiki/display/JAVA/Deploying+to+CloudMine's+Maven+Repo

From the root of the Java component's directory, execute:
mvn -DaltDeploymentRepository=snapshot-repo::default::file:{mavenRoot}/releases/ clean deploy
