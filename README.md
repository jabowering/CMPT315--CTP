#**Canadian Teacher's Portal**

##**Install instructions**

Required Packages

mySQL
Node 4.X

###Getting Started

```bash
 $ git clone https://github.com/afmartin/CMPT315--CTP.git
```

Create a mySQL database and specify the name of the database,
authorized username, password and the host inside of the db_config.json 

```bash
$ make test|development|production
```

Note - If you are running the test suites please ensure the server is
 running first. For example;

 $ npm install && NODE_ENV=test npm start

 and then in a new process

 $ make test

