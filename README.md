# Load balancer
Basic load balancer architecture assembled with nginx docker containers, managed with docker compose.

### You have two possibilities
- Use over HTTP
- Use over HTTPS

## How use

To run:  ```docker compose up -d```

To stop: ```docker compose down```




### URL´s: 
- http://mywebpage
- https://mywebpage

If you are going to use HTTPS, you need to put the certificates in the certs folder.

If you want to modify the URL, it is possible to do it in the Nginx file



## Previous configuration
You have to add the entry in the Host file

### In Linux:
Edit ```/etc/hosts``` file adding ```127.0.0.1  mywebpage```

### In Windows:
Edit ```C:\Windows\System32\drivers\etc\hosts``` file adding ```127.0.0.1  mywebpage```