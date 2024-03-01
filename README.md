Docker run on PORT 3306 inside Docker container.
Container expose the connection on Port 3307.

To connect:
```
mysql -P 3306 --protocol=tcp -u newuser1 -p
```
Default password is: password
