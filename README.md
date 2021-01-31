I used spring-boot, redis and docker.
Creating a redis docker image that is required first. To do this, you must have the docker desktop application installed on your computer. 
If you have a docker desktop installed on your computer, run the following command via command prompt.

command: docker run -p 6379:6379 --name yourImageName -d redis

After running the command, a docker image with redis running will be created. Then you will run the project. And open the chrome page.

write to chrome bar "http://localhost:8090/rest/user/add/1/adem" ->> this way we have added a person.

to list all persons   ->> "http://localhost:8090/rest/user/all" 

to delete one person  ->> "http://localhost:8090/rest/user/delete/id" 

to update one person  ->> "http://localhost:8090/rest/user/update/id/name" 
