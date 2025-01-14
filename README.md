"# Benchmarking-Consensus-Mechanisms-in-Microservice-Compotition" 

## Software installation requirements
    ●  Install java v19
    ●  Install maven
    ●  Sqlite database
    ●  Postman
    ●  Apache JMeter
    ●  Consul

------
### [Pitchfork Reviews Dataset](https://www.kaggle.com/nolanbconaway/pitchfork-data/data)

### [Consul](https://developer.hashicorp.com/consul)

### [Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi)

### [Kafka](https://kafka.apache.org/)

### [RabbitMq](https://www.rabbitmq.com/docs/download)

### [Docker](https://docs.docker.com/engine/install/)

### [Openjdk:19-alpine](https://hub.docker.com/layers/library/openjdk/19-alpine/images/sha256-32c1827093cd3070442939f5a60e611496e8632b02e8e5687ed328f0a23b2159)

------

- database.sqlite

| Table    | Total Rows | Total Columns |
|----------|------------|---------------|
| artists  | 18831      | 2             |
| content  | 18393      | 2             |
| genres   | 22680      | 2             |
| labels   | 20190      | 2             |
| years    | 19108      | 2             |
| reviews  | 18393      | 13            |


____
<details>
<summary>Microservice's</summary>

    ●  YearsService
    ●  ReviewsService
    ●  LabelsService
    ●  GenresService
    ●  ContentService
    ●  ArtistsService

```
   puts "ReviewsMicroservice"
```
</details>
____


### [Eureka-Server](https://github.com/Netflix/eureka/wiki/Eureka-at-a-glance)
```
Eureka is a RESTful service mainly utilized in the AWS cloud to locate services for load balancing and failover of middle-tier servers. This service is known as the Eureka Server. Additionally, Eureka includes a Java-based client component, the Eureka Client, which simplifies interactions with the service. The client features a built-in load balancer that performs basic round-robin load balancing. At Netflix, a more advanced load balancer enhances Eureka to offer weighted load balancing based on factors such as traffic, resource usage, and error conditions, ensuring greater resiliency.
```