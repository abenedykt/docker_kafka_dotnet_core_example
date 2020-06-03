# Dockerized kafka + dotnet core publisher + donet core consume exmaple


To start you'll need three terminals :) 

in the first one spinn up docker-compose

```
cd bitnami
run docker compose
```

in the second one run the consumer

```
cd kafka_consumer
dotnet run
```

and last but not least run the publisher


```
cd kafka_publisher
dotnet run
```

