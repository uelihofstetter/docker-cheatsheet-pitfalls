# docker-cheatsheet-pitfalls

### mysql
1. Use protocol=tcp to connect to mysql container on same host, i.e.

   mysql -u root -h localhost -P 3306 -p --protocol=tcp
