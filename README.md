# teamcity-node-agnet


## Build docker image

docker build -t teamcity-node-agent . 

## Run container

docker run teamcity-node-agent:latest -it -e SERVER_URL="<url to TeamCity server>" -v <path to agent config folder>:/data/teamcity_agent/conf
