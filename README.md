![Jenkins meta](https://raw.githubusercontent.com/jenkinsmeta/jenkinsmeta-docs/master/images/logo.png)

Jenkins meta is about decoupling Jenkins UI and CI processes. 


Frontend of Jenkins is used to present data from multiple CI masters, mainly, multiple Jenkins masters.

In backend the app is using Jenkins API to gather needed data from Jenkins masters. 


## Simplified architecture
![simplified arch](https://raw.githubusercontent.com/jenkinsmeta/jenkinsmeta-docs/master/images/architecture-simple.png)


## Jenkinsmeta-worker
As worker needs to be a standalone, configurable service, we need to configure everything related to jenkins master coupled with it, here.


## Planned architecture with multiple microservices deployed
![detailed arch](https://raw.githubusercontent.com/jenkinsmeta/jenkinsmeta-docs/master/images/architecture.png)
