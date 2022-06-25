# Mongo commands

Login mongo with user
```
$ mongo -u $USER -p $PASSWORD
```

Example to run commands js in mongo using eval
```
$ mongo -u $USER -p $PASSWORD --eval "rs.status()"
```