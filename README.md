# ELK-Stack-with-FileBeat

In this project, i have created simple integration of ELK stack with Filebeat to see the logs of the container. There is a dummy application which when running in the container simply generates the logs after 2 seconds. So you can see them into Kibana by creating its index.

I have also tested it by running a microservice image into the container and it was working perfectly by showing all the logs of the console of docker into the kibana.