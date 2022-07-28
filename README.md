# eDQL

#### Necessity is the mother of invention..!
This slogan made me enhance this project from DQL Tester FX framework.

Many tools supports the administration tasks on a Documentum environment. With this project a new version of 'DQL Tester FX' is under construction and made available.

We use the new JavaFX technology to create this standalone applications.

### Feature list
* Execute DQL queries with the result in a table view
* Browse the repository
* Dump and modify properties
* Administration tasks
    * Running jobs
    * User/Group management
    * Updates in security
* Execute API and DQL scripts

### Requirements for this application
* A Java Runtime Environment (JRE) (e.g. [OpenJDK Runtime Environment 18.9 (build 11.0.1+13)](https://jdk.java.net/))
* A runnable OpenText Documentum environment that can be pinged by hostname or IP-address from the machine where this application will be executed and ports (mentioned in dfc.properties) should be enabled.

### How to run the application:
1. Download the latest [release](https://github.com/parag4u/eDQL/releases) to the local drive.
2. Extract zip to local drive.
3. Update `dfc.properties` in the `config` directory with correct content.
4. Update `log4j.properties` with required changes in the `config` directory.
5. Check command prompt with "java -version" - command should return java (JRE) version 9 or above.
6. Execute eDQL.exe

# Coming up !!! eDQL - REST (based)
