This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command**

`docker run -d -u root --name jenkins \
    -p 8080:8080 -p 50000:50000 \
    -v /root/jenkins_2112:/var/jenkins_home \
    jenkins/jenkins:2.112-alpine`{{execute}}

after a while you can visit the UI on port 8080 with the URL: https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/