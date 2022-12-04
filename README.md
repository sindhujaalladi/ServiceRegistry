# ServiceRegistry

this service registry act as eureka server for registring the microservices and added default port as 8761 

![image](https://user-images.githubusercontent.com/115841974/205516323-3a788b29-512a-4a11-a55c-19bedfacd0fa.png)

![image](https://user-images.githubusercontent.com/115841974/205516330-6592dbf9-2de7-4bc8-95c3-58877c85ff67.png)


I have added OrderService and PaymentService as micro services and registred with this eureka server 
so i called PaymentService from OrderService as Microservice Instance name not with default url 



![image](https://user-images.githubusercontent.com/115841974/205516371-80a8f422-551d-44a0-b0f3-c5ad0bf1c8ae.png)


![image](https://user-images.githubusercontent.com/115841974/205516443-0e6108e2-b3af-48b8-baec-db854cd4784b.png)

If u mention as _ in application name u will face issue like Request URI doesnt have valid host
so give - not _
