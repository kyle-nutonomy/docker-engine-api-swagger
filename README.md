# docker-engine-api-swagger
Change tracking for modified docker engine api swagger

### Generate client for computation server using openapi-generator-cli.jar: 

rm -rf Generated/DockerAPI && java -jar /opt/openapi/openapi-generator-cli.jar generate -i <path-to-modified-swagger.yaml-file> -o Generated/DockerAPI -g csharp-netcore -c <path-to-config.yaml-file>