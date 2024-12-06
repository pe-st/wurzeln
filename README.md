# Root POMs

## Commands

```bash
mvn clean install
mvn clean verify -P dependencies-existence

cd update-checker
mvn -P update-check
mvn clean dependency:tree -P update-check
```

## Notes

### log4j-api-java9 / log4j-core-java9

`[WARNING] The POM for org.apache.logging.log4j:log4j-api-java9:zip:2.13.3 is missing, no dependency information available`

Ignore the warnings, see <https://issues.apache.org/jira/browse/LOG4J2-3241>
