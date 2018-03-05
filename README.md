# nimity-test
This project has the following:
1. A Public Page (General-Page)
2. A Login Page (Login-Page)
3. A Secured Page (Product-Page)

Once a successful login, the Product-Page will be available where the user can choose any Category to view the Products under this Categoty. An API was designed to pull data from Northwind database via Entity Framework

Technologies used:
1. UI - Angular 4.x
2. DB MS SQL (Northwind Database - Category/Product tables)
3. Web API was designed and implements.
4. CORS included in order to resolve access problem when both UI & API run on localhost
5. Security: It supposed to be JWT, but not included. Currently username: user1, password: pass1
6. DI: there are two services implemented.
  - Message service: to communicate between Components
  - Data service: to Pull data from Nothwind database
  
  both services were injucted in the required components, which satisfied the DI requirements
7. SOA is implemented in API design 


