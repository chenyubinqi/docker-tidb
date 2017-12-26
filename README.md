+ Use `docker-compose up -d` to create and start the cluster.
+ Use `docker-compose port tidb 4000` to print the TiDB public port. For example, if the output is `0.0.0.0:32966`, the TiDB public port is `32966`.
+ Use `mysql -h 127.0.0.1 -P 32966 -u root -D test` to connect to TiDB and enjoy it.
+ Use `docker-compose down` to stop and remove the cluster.
