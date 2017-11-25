## Fork of Java and Mongodb Rapid App Prototyping  
  
 Fixed bugs and Played around with Dropwizard framework functionality 
  
[![DropWizard](http://techbus.safaribooksonline.com/static/201711-8221-techbus/images/9780134070872/9780134070872_s.jpg)]

# Technology Stack  
Angular, HTML5, JavaScript, Bootstrap,  Java, Dropwizard, MongoDB, Groovy, Gradle

How to run this example ?
-------------------------

- Install Mongodb with Default Configurations,  start the database.
- Load the project into IntelliJ, Navigate to Build Menu on Toolbar and Hit Rebuild Project  
- Run the gradle build -> gradle clean build jar -x test  
- Navigate to coffee-shop-the-app\src\main\java\scripts\PopulateDatabase.groovy,  
right click on source editor and select Run PopulateDatabase from context menu,  
will load documents to mongodb.  
- Navigate to coffee-shop-the-app\src\main\java\com\mechanitis\demo\coffee\CoffeeShopService.java 
- run the file run configurations pass the program arguments server coffee.yaml if not exists 

[![configurations](https://image.prntscr.com/image/EnfL52o9TxWtCP7c8kR4sA.png)]  

- browser endpoint http://localhost:8080/coffee.html


What next?
----------------------------
Go through the source and try out the sample    

Keep Learning and share your knowledge.  
Many Thanks to Trishagee


  
