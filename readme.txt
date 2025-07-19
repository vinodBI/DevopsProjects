<<<<<<< HEAD
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
=======
2nd Project Objectives:

1. Setup a basic project 
2. Configure inheritance between projects
3. Modify projects using profiles
4. Setup a project using the archetype plugin

   Note: Standard directory layout need to be followed as it is very important for how maven performs

5. Create a new Java project and pom.xml file from scracth using IDE IntelliJ
>>>>>>> c9ac7d0 (maven-examples project is about creating blank java project files and pom.xml from scratch and changing the maven standary layout directory of source and target files in pom.xml)

create a maven project from internal archetype
mvn archetype:generate -DarchetyeCatalog=internal 
created maven simple site project 9
 
we will use this simple-site project pom file as parent file for the pom file in maven-examples project





