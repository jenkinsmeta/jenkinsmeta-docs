Interfaces
==========






Interface Web <-> Server
========================

##GET /exeutors

response:
```python 
{'master': {'executors': 2, 'jobs_active': [], 'offline': False},
 'slave': {'executors': 4,
             'jobs_active': [{'name': {'color': 'blue_anime',
                                       'name': 'tete',
                                       'url': 'http://',
                                       'time':{'remaining':'1s', 'started':'2s'},
                                       },
                              'number': '23'},
                             {'name': {'color': 'blue_anime',
                                       'name': 'tete',
                                       'url': 'http://localhost:8080/job/tete/',
                                       'time':{'remaining':'1s', 'started':'2s'},
                                       },
                              'number': '22'}],
             'offline': False}}
````


##GET /queue

response:
````python
{ 'jobname':{'time_': ''}}
```


##GET /views/

response:
````python
{'kekeke': {'url':'http://local/views/kekeke'}}
{'buildbot-kek':{'url':'http://local/views/myview'}
````


##GET /views/:name

response:
````python
{'jobs':{'name':{'status':'building '}}}
````
