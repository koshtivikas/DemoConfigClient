# DemoConfigClient
DemoConfigClient Repo

# Details
1. Create a rest endpoint to access the propery.
    http://localhost:8080/msg/ 
    
2. IF we want to refesh properties. We need invoke following enpoint from  POSTMAN rest testing. Ths will refresh the properties if there are any new changes on gitHub.
    http://localhost:8080/actuator/refresh
    
3. Following properties are added to enable the refresh endpoint. 
      i.  management.security.enabled=false
      ii. management.endpoints.web.exposure.include=*
