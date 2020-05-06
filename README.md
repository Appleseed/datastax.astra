# Leaves.Astra 

Leaves on DataStax Astra™ with NoSQL, and Apache Cassandra™ in the cloud!

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://github.com/xingh/leaves.astra.git)

## Getting started

```sh
Git clone https://github.com/xingh/leaves.astra.git
cd leaves.astra/
```

## Credentials
**IMPORTANT**

1. 
* On Astra, download your secure connect bundle:

![SecConImg](Assets/Images/DownloadSecureCon.png)

* Add the `secure-connect-CLUSTER_NAME.zip` to **leaves.astra/astra.credentials/**

2. 
* Modify each field value in **leaves.astra/astra.credentials/UserCred.json** 

<img src="Assets/Images/UserCred.png" width="500" height="300">

## RUN DATA MIGRATOR
- - - 

```
python3 astra.import/data/RESTToAstra.py
```

### APIs
---

#### NODE.JS

[README](https://github.com/xingh/leaves.astra/blob/master/astra.api/leaves.api.node/README.md)

#### PYTHON

[README](https://github.com/xingh/leaves.astra/blob/master/astra.api/leaves.api.python/README.md)

##### Response:
```
[...] // # of articles
```


### TESTING
--- 

[README](https://github.com/xingh/leaves.astra/blob/master/astra.api/leaves.api.tests/README.md)
