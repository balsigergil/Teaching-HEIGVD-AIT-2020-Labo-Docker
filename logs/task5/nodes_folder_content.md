# Nodes list

The content of `/nodes` folder in ha container.

## After ha started
The folder is empty.

## After 1st web app started
```
$ docker-compose exec haproxy ls /nodes                                                            
10916ba8323d
```

## After 2nd web app started
```
$ docker-compose exec haproxy ls /nodes                                                            
10916ba8323d  d5710818afbb
```

## After closing webapp1
```
$ docker-compose stop webapp1                                                                       
Stopping s1 ... done

$ docker-compose exec haproxy ls /nodes                                                             
d5710818afbb
```