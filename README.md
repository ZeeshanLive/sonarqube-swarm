# sonarqube-swarm


to deploy SonarQube Stack into the swarm cluster

cd into sonarqube directory and run the below command
docker stack deploy -c docker-compose.yaml sonarqubestack

to remove the stack 
docker stack rm sonarqubestack

docker stack ps - to list out the stacks
