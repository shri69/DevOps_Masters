# DevOps_Masters
DevOps_Masters


Started Devops Masters on April 21-04-2023

Jenkins integration
 1.open Jenkins
 2.click on new item
 3.Give a name to the job
 4.select free style job
 5. select git in source code management
 6. add the repository 
 7. click applyand save 

Maven integration
1.open Jenkins
 2.click on new item
 3.Give a name to the job
 4.select free style job
 5. select git in source code management
 6. add the repository 
 7. select Execute shell in Build Actions
  add the below commands
   cd 5-Jenkins/5.3-Maven project/myapp

   mvn clean install

   tree 

   java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App

   Terraform commands
   terraform init
   terraform plan
   terraform apply 
   terraform out put



