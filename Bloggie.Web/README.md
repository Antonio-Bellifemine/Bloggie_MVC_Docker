## To pull and image and run a container, run thi command in the root terminal
1. install docker desktop
2. docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=2Secure*Password2" -p 1450:1433 --name BloggieDb -h BloggieDb -d mcr.microsoft.com/mssql/server:2019-latest 
