The telegraph config file is fully updated


HOW TO RUN THIS CODE:
1. change the username and password according to your requirement
2. change the database name according to your requirement
3. in the terminal run this command:
   
   ```docker-compose up -d```

4. in order to check the status of the container running

   ```docker ps```


Only things to be kept in mind is that in the grafana while adding the influx db 

1. add the exact same name of the database
2. add the correct username given in the telegraf.conf file
3. add the correct password given in the telegraf.conf file
4. IN THE AUTH section :
    a) Check the basic auth radio box
    b) Check the with credentials radio box


   
