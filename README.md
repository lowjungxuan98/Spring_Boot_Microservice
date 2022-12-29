# Spring Boot Microservice

## Overview Diagram
![microservice-overview](mircoservice-overview.png)

## API Gateway
API Gateway帮助所有的module统一了所有的path

正常情况下我们call api需要以指定的Path来读取指定的module
![traditional](traditional.png)
API Gateway为了简化和improve前端开发，API将所有的module统一化
![api_gateway](api_gateway.png)