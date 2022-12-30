# Spring Boot Microservice

## Overview Diagram
![mircoservice-overview](image/mircoservice-overview.png)

## API Gateway
API Gateway帮助所有的module统一了所有的path

正常情况下我们call api需要以指定的Path来读取指定的module
![traditional](image/traditional.png)
API Gateway为了简化和improve前端开发，API将所有的module统一化
![api_gateway](image/api_gateway.png)