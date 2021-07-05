# Devops_Project

# Installing hadoop on ubuntu machine
``

wget https://downloads.apache.org/hadoop/common/stable/hadoop-3.3.1.tar.gz
``
```wget https://downloads.apache.org/hadoop/common/stable/hadoop-3.3.1.tar.gz
--2021-07-05 02:45:04--  https://downloads.apache.org/hadoop/common/stable/hadoop-3.3.1.tar.gz
Resolving downloads.apache.org (downloads.apache.org)... 135.181.214.104, 88.99.95.219, 135.181.209.10, ...
Connecting to downloads.apache.org (downloads.apache.org)|135.181.214.104|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 605187279 (577M) [application/x-gzip]
Saving to: ‘hadoop-3.3.1.tar.gz’
```

## Transfer hadoop to containers

`
docker cp hadoop-3.3.1.tar.gz namenode:/
ubuntu@ip-172-31-16-251:~/docker$ docker cp hadoop-3.3.1.tar.gz datnode1:/
no such directory
ubuntu@ip-172-31-16-251:~/docker$ docker cp hadoop-3.3.1.tar.gz datanode1:/
ubuntu@ip-172-31-16-251:~/docker$ docker cp hadoop-3.3.1.tar.gz datanode2:/
ubuntu@ip-172-31-16-251:~/docker$ 
`

