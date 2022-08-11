# cloud-parking
REST API created for a parking. I created this using Java and Spring Boot framework

This projected is about a REST API to manage a parking. 

I did this with Java 18 + Spring Boot.

I used DTO design pattern. It is one of the EPA patterns which we call when we need to use such objects that encapsulate and aggregate data for transfer.

Whats is a DTO?

"A DTO is similar to a data structure, but like a data structure, it doesn't contain any business logic. It contains mechanisms of serialization and de-serialization. In DTO, we can store data from a single source or from multiple resources. We can either store complete data or can store a small amount of data from a source." 

![Screen Shot 2022-08-11 at 13 00 11](https://user-images.githubusercontent.com/105367430/184177676-f2eafd66-c16f-42f4-8fe2-8193a51253ed.png)

I used the library Model Mapper. The main role of ModelMapper is to map objects by determining how one object model is mapped to another called a Data Transformation Object (DTO).

![Screen Shot 2022-08-11 at 13 02 58](https://user-images.githubusercontent.com/105367430/184178247-1d50443e-b03a-4eee-8b08-8480caeaadfd.png)

I used Swagger to visualize and test my API.



https://user-images.githubusercontent.com/105367430/184196462-6f9b6247-ec3c-4ff5-8c13-7a14ca2391c5.mov

I used Docker as well to run a Postgres image.

I need to config security with Spring security dependecy, and it's the next step of the project.

Thanks for reading it.








