# Customer UserData Application Using Spring Boot, Spring Security, JWT, JPA, React.Js and MySql

## Requirements

1. Java >= java 11

2. Maven - 3.x.x

3. Mysql - 5.x.x

4. lombok

5. VsCode

6. Vite-React App

## Steps to Setup

**1. Clone the application**

```bash
git clone https://github.com/DhanushIndrakumar/Sunbase.git
```
**2. Key points of the application**

+ The Backend files and Frontend files for the application are in 2 different folders.

+ The Frontend was done using Vite-React app through VSCode.

+ The Backend was implemented using Spring Boot through IntellijIdea.

+ The company folder contains backend files.

+ The frontend folder contains frontend files.


**3. Run the Backend application**

+ open `company/src/main/resources/application.properties`

+ change `spring.datasource.username` and `spring.datasource.password` as per your mysql installation

+ after changing both the username and password as per your mysql installation
  
+ we can run it from NetBeans or intellij IDEA.

+ The app will start running at http://localhost:2000/**
  
+ .Since the port is set to localhost:2000 and the user is free to change the port if they wish.

**4. Explore Rest APIs **

+ Once the backend is working. Developer can go through the OpenApi documentation as it gives more understanding and working of the APIs.

 ![Capture](https://github.com/DhanushIndrakumar/Sunbase/assets/111871670/8d61a020-e1d0-423f-8148-3b61fb6c3406)

+ We can see the API Documentation at

```bash
    http://localhost:2000/swagger-ui.html
```
+ we need to first execute the register and login user APIs for the other APIs to work.

**5. Exploring the Api to insert or create User(Customer) in the database **

+ The request body of the API with the response body is shown below:

  ![Capture2](https://github.com/DhanushIndrakumar/Sunbase/assets/111871670/22f803a8-880f-4c0e-a8b5-bd6336262841)

**6. Testing the Login Api

+ Api works in OpenApi documentation as well.The image below shows the request and the response body of the Login Api

  



  

  

  

