# Run SonarQube in ECS Fargate cluster
Included "-Dnode.store.allow_mmap=false" in sonar.sh to disable the bootstrap check for elasticsearch. 
