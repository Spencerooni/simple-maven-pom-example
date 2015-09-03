Simple Java console app which:
- gets built into a fat jar
- uses managed dependencies from maven

```bash
cd my-app
mvn clean compile assembly:single
java -jar target/my-app-1.0-SNAPSHOT-jar-with-dependencies.jar
```
