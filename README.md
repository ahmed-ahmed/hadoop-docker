# hadoop-docker

## To Pull image 

```sh 
docker pull ahmedahmed/apache
docker pull ahmedahmed/hadoop-docker

```

## To build image 
```sh 
docker build -t hadoop .
```

## To run image 
```sh 
docker run -it -p 50070:50070 -p 9000:9000 -p 50030:50030 -p 8088:8088  hadoop
```

## to change configurations 

change the configuration in the xml files 

