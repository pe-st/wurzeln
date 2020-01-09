# Root POMs

## Commands

    mvn clean install
    mvn clean verify -P dependencies-existence

    cd update-checker
    mvn -P update-check
    mvn clean dependency:tree -P update-check
