-- create init project
   mvn archetype:generate -B \
       -DarchetypeCatalog=https://github.com/spark-in-action/scala-archetype-sparkinaction/raw/master/archetype-catalog.xml \
       -DarchetypeRepository=https://github.com/spark-in-action/scala-archetype-sparkinaction/raw/master \
       -DarchetypeGroupId=org.sparkinaction \
       -DarchetypeArtifactId=scala-archetype-sparkinaction \
       -DarchetypeVersion=0.12 \
       -DgroupId=com.company -DartifactId=project -Dversion=0.1-SNAPSHOT -Dpackage=com.company

-- clean and package project
   mvn clean package -U


scala test 官方文档：
  http://www.scalatest.org/user_guide/using_matchers

https://github.com/spark-in-action/scala-archetype-sparkinaction
https://github.com/spark-in-action