# BaseJaaC
A little base repository jenkins as a code. 

Command to help you run Jenkins and test up:

- docker build -t jenkins:jcasc .
- docker run --name jenkins --rm -p 8080:8080 --env JENKINS_ADMIN_ID=admin --env JENKINS_ADMIN_PASSWORD=password jenkins:jcasc

When need to stop:
- docker stop jenkins