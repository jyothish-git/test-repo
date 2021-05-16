# Run SonarQube in ECS Fargate cluster
- Included jvm option "-Dnode.store.allow_mmap=false" in sonar.sh to disable the bootstrap check for elasticsearch. 
- To change the value of vm.max_map_count you need to access to your host. Farage is a serverless service and you can't access your host.
