Interfaces
==========


GET /queue

response:
{ 'jobname':{'time_': ''}}




----------

PUT /queue 
{'id':{''}}i




Interface Web <-> Server
========================

GET /exeutors
response:
{'master': {'executors': 2, 'jobs_active': [], 'offline': False},
 'slaveek': {'executors': 4,
             'jobs_active': [{'name': {'color': 'blue_anime',
                                       'name': 'tete',
                                       'url': 'http://localhost:8080/job/tete/',
                                       'time':{'remaining':'kek', 'started':'lol'},
                                       },
                              'number': '23'},
                             {'name': {'color': 'blue_anime',
                                       'name': 'tete',
                                       'url': 'http://localhost:8080/job/tete/',
                                       'time':{'remaining':'kek', 'started':'lol'},
                                       },
                              'number': '22'},
                             {'name': {'color': 'blue_anime',
                                       'name': 'tete',
                                       'url': 'http://localhost:8080/job/tete/',
                                       'time':{'remaining':'kek', 'started':'lol'},
                                       },
                              'number': '21'},
                             {'name': {'color': 'blue_anime',
                                       'name': 'tete',
                                       'url': 'http://localhost:8080/job/tete/',
                                       'time':{'remaining':'kek', 'started':'lol'},
                                       },
                              'number': '20'}],
             'offline': False}}


GET /queue
response:
{...}


GET /views/
response:
{'kekeke': {'url':'http://local/views/kekeke'}}
{'buildbot-kek':{'url':'http://local/views/myview'}


GET /views/:name
response:
{'jobs':{'name':{'status':'building '}}}
