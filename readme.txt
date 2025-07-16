Hello...

This is first project on Maven
1. This project is created using the quickstart Archetype from the internal maven repository
2. command to create the project is
   mvn archetype:generate -DarchetypeCatalog=internal
3. slect the number of quickstart project
4. give group id, artifact id, version packaging type as jar
   Note: if packaging type not asked at the time of creation you can add <packaging>jar</packaging> in pom.xml file after creating the porject

project will be created
with a pom.xml file and a source folder with main java code and test codes

5. run mvn package to create jar file in the target folder
Project completed. Push it to git hub repository.

git remote add origin https://github.com/vinodBI/DevopsProjects.git
git branch -M main
git push -u origin main

:wq


