# Ecommerce Backend

## Software Required

1. Java 17
2. MySQL 8 & SQLYog
3. MongoDB 6 & MongoDB Compass
4. IntelliJ Idea
5. ZipKin Server


## Steps To Start Projects

1. Open all projects in IntelliJ Idea
2. Build the all projects using maven :- `mvn clean install`
3. First run `ServiceRegistry`
4. Then run `Wishlistservice` , `OrderService` , `CartService` , `ApiGateway` , `UserService`

   **Note: If you `PostgreSQL` in your system then change spring profile test to dev in `application.yml` for
   CartService & WishlistService and create database accordingly**

5. For `ProductService` please open this project in `new window`

   **Note: If you open in same window for save & update product functionality it give `404 exception - File Not Found`**

6. Please download Zipkin Server from [here](https://zipkin.io/pages/quickstart.html). Paste
   the `zipkin-server-2.23.19-exec` file in `ECommerceApp-Backend` folder. Open `cmd` from ECommerceApp-Backend location
   type `java -jar zipkin-server-2.23.19-exec` enter

## Important URL'S

1. Service Registry `Port - 8761` :- [Eureka Server](http://localhost:8761/)
2. API Gateway `Port - 9000` :-

   **Note: For Gateway API Documentation Please Use Postman**

3. User Service `Port - 9001` :- [API Documentation For User Service](http://localhost:9001/swagger-ui/index.html)
4. Product Service `Port - 9002` :- [API Documentation For Product Service](http://localhost:9002/swagger-ui/index.html)
5. Cart Service `Port - 9003` :- [API Documentation For Cart Service](http://localhost:9003/swagger-ui/index.html)
6. Order Service `Port - 9004` :- [API Documentation For Order Service](http://localhost:9004/swagger-ui/index.html)
7. Wishlist
   Service `Port - 9005` :- [API Documentation For Wishlist Service](http://localhost:9005/swagger-ui/index.html)
8. Hystrix Dashboard `Port - 9009` :- [Hystrix Dashboard](http://localhost:9009/hystrix)
9. Zipkin Server `Port - 9411` :- [Zipkin Server](http://127.0.0.1:9411/)
10. Admin Server `Port - 8761` :- [Spring Boot Admin Server](http://localhost:8761/admin)