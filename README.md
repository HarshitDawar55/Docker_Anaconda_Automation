# Docker_Anaconda_Automation

:sparkles::fireworks::tada: Important points about this Repository!!!!! :tada::fireworks::sparkles: 

- This repository contains a docker compose file which will download the official anaconda image and will run the docker container with name "anacondafull". 
- Also, the environment created will have 2 environment variables pre-defined by me, they correspond to custome environment name and a package to be installed in that environemnt.
- One package variable can take 1 package, so, if mutplie packages have to be installed then, multiple variables can be created for that.

# Executing the File!

- In order to execute the file, you have to just run this command "docker-compose up".


# What to do after executing the file!

- After executing the file, you have to open a new terminal, and using this command "docker exec -i -t anacondafull bash", you will be able to gain the access to the anaconda OS. 
- From there, all the operations can be performed normally as they could have been done in the anaconda software.
- To create the environment specified in the script, use command "conda create --name $environment_name".


# LICENSE

To check the license visit [LICENSE](https://github.com/HarshitDawar55/Docker_Anaconda_Automation/blob/master/docs/LICENSE.md) 

