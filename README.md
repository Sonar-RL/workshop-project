



## 1. import and clone repo to local

 git clone https://{user_name}:{token}@github.com/{org_name}/workshop-project.git  
 
 
## 2. manual scan
 
mvn clean install -DskipTests=true sonar:sonar -Dsonar.host.url=https://sonarcloud.io  -Dsonar.token=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
