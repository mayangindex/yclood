## Getting Started after Deployment

#### Access Kibana

To access the front end interfaces for either ELK, first obtain the credentials. Then, open your web browser and navigate to the Location URL of the app you wish to access. In the login prompt that appears, enter the username and password as shown in the credentials file.

Obtain the Credentials

Once logged in, run the following command:

cat /opt/elk/credentials
This displays the credentials and endpoint URL for Kibana, as shown in the example output below.

```
#####################
###### Kibana #######
#####################
Location: http://192-0-2-1.nip.io
Username: elastic
Password: htyjuykuy
```
