```
[INFO] Scanning for projects...
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] Building bnd-bug-20180519 0.0.1
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ bnd-bug-20180519 ---
[INFO] Deleting /home/rm/git/com.github/io7m/bnd-bug-20180519/target
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ bnd-bug-20180519 ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/rm/git/com.github/io7m/bnd-bug-20180519/src/main/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ bnd-bug-20180519 ---
[INFO] No sources to compile
[INFO] 
[INFO] --- bnd-maven-plugin:4.0.0:bnd-process (osgi-manifest) @ bnd-bug-20180519 ---
[WARNING] /home/rm/git/com.github/io7m/bnd-bug-20180519/pom.xml [0:0]: No translation found for macro: project.licenses[0].name
[WARNING] /home/rm/git/com.github/io7m/bnd-bug-20180519/pom.xml [0:0]: The JAR is empty: The instructions for the JAR named bnd-bug-20180519 did not cause any content to be included, this is likely wrong
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ bnd-bug-20180519 ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/rm/git/com.github/io7m/bnd-bug-20180519/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.1:testCompile (default-testCompile) @ bnd-bug-20180519 ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ bnd-bug-20180519 ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:3.0.0:jar (default-jar) @ bnd-bug-20180519 ---
[INFO] Building jar: /home/rm/git/com.github/io7m/bnd-bug-20180519/target/bnd-bug-20180519-0.0.1.jar
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 1.688 s
[INFO] Finished at: 2018-05-19T18:04:05+01:00
[INFO] Final Memory: 12M/47M
[INFO] ------------------------------------------------------------------------

$ unzip -p target/bnd-bug-20180519-0.0.1.jar META-INF/MANIFEST.MF
Manifest-Version: 1.0
Archiver-Version: Plexus Archiver
Created-By: Apache Maven 3.5.2
Built-By: rm
Build-Jdk: 10.0.1
License: ISC License

$ cat target/classes/META-INF/MANIFEST.MF 
Manifest-Version: 1.0
Bnd-LastModified: 1526749383524
Bundle-ManifestVersion: 2
Bundle-Name: bnd-bug-20180519
Bundle-SymbolicName: bnd-bug-20180519
Bundle-Version: 0.0.1
Created-By: 10.0.1 (Oracle Corporation)
License: ${project.licenses[0].name}
Tool: Bnd-4.0.0.201805111645
```
