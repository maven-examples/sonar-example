## Articles
- http://confluence.marcuschiu.com/x/bIGFAQ
- https://docs.sonarqube.org/latest/analysis/scan/sonarscanner-for-maven/

## Invoke Sonar Scan
mvn sonar:sonar \
-Dsonar.projectKey=com.marcuschiu:sonar-example \
-Dsonar.host.url=http://ubuntu-server.local:9000 \
-Dsonar.login=8c6c5023c94d72208e4d417f0105ab01a3c69f44