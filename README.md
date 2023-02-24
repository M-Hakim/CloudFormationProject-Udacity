# CloudFormationProject-Udacity

## Project diagram
![Project diagram](images/project-diagram.png)

## To run the project for the first time

1- Run The network stack, and wait untill it's done
```
$ ./create.sh network-stack network.yml network-parameters.json
```
2- Run The servers stack, and wait untill it's done
```
$ ./create.sh servers-stack servers.yml server-parameters.json

## Screenshots
![Network Stack Created](images/network-stack.png)
![Server Stack Created](images/servers-stack.png)
![Webapp DNS Output](images/webapp-dns-output.png)
![Webapp Homepage](images/webapp-homepage.png)

## To update the project after creation
```
$ ./update.sh <stack-name> <template-body-file> <parameters-file>
```

## To delete a stack
```
$ ./delete.sh <stack-name>
```
