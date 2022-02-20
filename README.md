# nestjs-kafka-microservices :sunglasses:

This is a very simple project using NestJS Framework + Kafka to create microservices architecture, based on [Michael Guay' Video](https://www.youtube.com/channel/UChNA2S9dtoEMAVGPddbDIJg).

###  How to setup :heavy_check_mark:	

Clone this repository and use Docker to up Kafka, here we are using the [Kafdrop – Kafka Web UI](https://github.com/obsidiandynamics/kafdrop).
```
docker-compose up -d 
```
So start the projects using YARN:
```
yarn start:dev
```
or using NPM:
```
npm run start:dev
```
Use the endpoint POST http://localhost:3000 for test the communication between api gateway and microservices, using payload below:
```json
{
    "userId": "345",
    "price": 35.334
}
```
:crossed_fingers:	:partying_face:	

