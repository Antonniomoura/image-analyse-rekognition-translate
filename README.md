## Description
##### Installation

```bash
$ npm install
```

##### Running the app

```bash
# run serveless local
$ sls invoke local  -f img-analyse --path request.json
 
# run serveless prod
$ sls invoke  -f img-analyse --path request.json 
```

##### Deploy
```
$ sls deploy
```