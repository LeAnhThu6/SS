# SS

  compileOnly('jakarta.platform:jakarta.jakartaee-web-api:10.0.0')
  implementation('org.glassfish.jersey.core:jersey-client:3.1.2')
  implementation('org.jboss.weld.se:weld-se-core:5.1.0.Final')

  testImplementation("org.junit.jupiter:junit-jupiter-api:${junitVersion}")
  testRuntimeOnly("org.junit.jupiter:junit-jupiter-engine:${junitVersion}")
  implementation 'org.mariadb.jdbc:mariadb-java-client:3.2.0'
  implementation 'org.eclipse.persistence:eclipselink:4.0.2'

  //lombok
  compileOnly 'org.projectlombok:lombok:1.18.20'
  //for logging
  implementation 'org.slf4j:slf4j-api:2.0.9'
  implementation 'org.slf4j:slf4j-simple:2.0.9'
  //json
    implementation 'com.fasterxml.jackson.core:jackson-databind:2.12.4'
