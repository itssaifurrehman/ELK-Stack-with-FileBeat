# ELK-Stack-with-FileBeat

In this project, i have created simple integration of ELK stack with Filebeat to see the logs of the container. There is a dummy application which when running in the container simply generates the logs after 2 seconds. So you can see them into Kibana by creating its index.

I have also tested it by running a microservice image into the container and it was working perfectly by showing all the logs of the console of docker into the kibana.

Go into the root of the folder and run this command to start it up

docker-compose -f docker-compose.yml up -d

Check all the 5 container are running perfectly or not

docker-compose -f docker-compose.yml ps

Now go to Kibana(http://localhost:5601/ and create index there and start visualizing the logs.