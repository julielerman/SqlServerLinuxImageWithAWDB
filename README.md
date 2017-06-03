# SQL-Server-Linux-Docker-Test
Files to accompany July 2017 MSDN Magazine Data Points (url provided when it's live).

This is for building a docker image that relies on Microsoft's mssql-sqlserver-linux image and adds in to pre-create a simple database with a single table with 2 rows of data.

Build the image with :
docker build -t julielinuximage .

Build the container with:
docker run -d  -p 1433:1433  --name juliesqllinux julielinuximage

You'll find the rest of the details in the article.
