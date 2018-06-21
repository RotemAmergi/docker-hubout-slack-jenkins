# docker-hubout-slack-jenkins
#How to use the image :<br>
1)Clone the repo .<br>
2)Build the docker image .<br>
`docker build -t NAME_OF_THE_IMAGE:TAG .`<br>
The docker image base on the nodejs latest image .<br>
#Set the Env setting in the docker compose<br>
1)Add hubot app to your slack workspace and save the token .<br>
2)Edit the docker-compose for :<br>
+ HUBOT_SLACK_TOKEN (required)<br>
+ HUBOT_JENKINS_URL (optional. if you wanna integrates with jenkins)<br>
+ HUBOT_JENKINS_AUTH (optional. if you wanna integrates with jenkins)<br>
