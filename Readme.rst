Qom Web Site 
============

Qom is a new hydrograph prediction model enhanced with multi-objective optimization ... (this site is under construction)


Requirements
------------

Qom is based on the 6.0-SNAPSHOT version of jMetal. To use that dependence it is necessary to include a file called ``settings.xml`` in the ``.m2`` directory located in the user home directory (if the file does exist, just add the code in the ``<profiles>`` section)::

  <settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
      xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
      xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0
                          http://maven.apache.org/xsd/settings-1.0.0.xsd">
   <profiles>
     <profile>
      <id>allow-snapshots</id>
        <activation><activeByDefault>true</activeByDefault></activation>
      <repositories>
       <repository>
         <id>snapshots-repo</id>
         <url>https://oss.sonatype.org/content/repositories/snapshots</url>
         <releases><enabled>false</enabled></releases>
         <snapshots><enabled>true</enabled></snapshots>
       </repository>
      </repositories>
     </profile>
   </profiles>
  </settings>

