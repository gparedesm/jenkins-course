# Jenkins
## Run Jenkins container
`docker-compose up -d`

This inicialice jenkins container in your machine. If you want to create a local DNS in order to access, go to `C:\Windows\System32\Drivers\etc\hosts` and edit it as administrator. Add: `<your_IP> dns.name` .

## Copy password
Open jenkin's container logs and copy printed password in order to access the first time. Then change it and put what you wish.

`docker logs jenkins`

