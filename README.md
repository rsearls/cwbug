
This project has been created to show a cli bug on Windows.
It is intended to show the failure in a github CI.

The user can run the test locally with the following cmd

    mvn clean install -PLocal -Dserver.home=${YOUR_WILDFLY_HOME}/ee-9/dist/target/wildfly-preview-27.0.0.Alpha4-SNAPSHOT

mvn clean install -PLocal \
    -Dserver.home=/home/rsearls/j1/wildfly/ee-dist/target/wildfly-27.0.0.Alpha4-SNAPSHOT


