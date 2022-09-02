# quarkus-dashboards Project


To build the project use:

```
mvn clean install
```

Then run the JAR:

```
java -jar target/quarkus-app/quarkus-run.jar
```

To edit dashboard modify the file `hello.dash.yaml`. You can change the file `setup.js` to map new dashboards.

Run in dev mode:, edit the dashboard and the changes should be visible after refresh:
```
mvn clean compile quarkus:dev
```
