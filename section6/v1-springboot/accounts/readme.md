- add configuration details using @Value 
- add api get info in controller file 


- Add Environmet variable - private Evnironment environment;
- add api java-version in controller 
- also use Autowire tag


- Add Configuration details in Yaml file like this accounts:
  message: "Welcome to Dev accounts related local APIs"
  contactDetails:
  name: "Dev - Developer"
  email: "dev@dev"
  
- add @EnableConfigurationProperties tag in main application.java file
- create new dto class and add all configuration  that we added in Yaml file
- import that file using @EnalbleConfigurationProperties(value= "dto clas")
- create api path for it


- create new application_prod.yml and application_qa.yml file
- now add spring config activat on application.yml file
- run the command and make sure version 2.0 shown in build-value api
- for activate profile use profiles:active: "qa"