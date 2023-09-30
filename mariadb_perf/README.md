
docker run -d -p 3307:3306 --shm-size=512m -e PM1=mcs1 --hostname=mcs1 --name mcs1 mariadb/columnstore

docker cp "C:\Users\A108587977\git\tpch_data\sf1\" e27:/tmp/

https://github.com/catarinaribeir0/queries-tpch-dbgen-mysql/blob/master/README.md