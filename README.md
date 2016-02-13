![Jenkins meta](https://raw.githubusercontent.com/jenkinsmeta/jenkinsmeta-docs/master/images/logo.png)

Jenkins meta is about decoupling Jenkins UI and CI processes. 


Frontend of Jenkins is used to present data from multiple CI masters, mainly, multiple Jenkins masters.

In backend the app is using Jenkins API to gather needed data from Jenkins masters. 


## Simplified architecture
![simplified arch](https://raw.githubusercontent.com/jenkinsmeta/jenkinsmeta-docs/master/images/architecture-simple.png)


## Jenkinsmeta-worker
As worker needs to be a standalone service, we need to pass whole configuration for jenkins master coupled with it, in each call, as it has to be an stateless API.


So, server has to pass hostname+port with each call. Theoretically, it also needs to pass call type: if jenkins API will be called or some different CI API.

## Planned architecture with multiple microservices deployed
![detailed arch](https://raw.githubusercontent.com/jenkinsmeta/jenkinsmeta-docs/master/images/architecture.png)
