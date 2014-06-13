


* Compile the application by running `mvn clean compile dependency:copy-dependencies -DstripVersion`


* To try with a *distributed* cache, run the following command in separated terminals:
    * `java -cp "target/classes:target/dependency/*" org.infinispan.quickstart.clusteredcache.Node -d LEFT`
    * `java -cp "target/classes:target/dependency/*" org.infinispan.quickstart.clusteredcache.Node -d RIGHT`


