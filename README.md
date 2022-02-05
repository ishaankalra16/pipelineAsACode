# Vprofile-project
A demo application integrated, tested and analysed with the tools such as Jenkins, Nexus, SonarQube that send every notification to desired slack regarding every build of the pipeline. Instead of creating separate jobs to achieve the desired goal, a JenkinsFile is used with the aid of which we can control the pipeline with the help of code written in the JenkinsFile.

# Prerequisites
#
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL

# Architecture 

<img width="685" alt="152109592-a3629c85-2562-4ca5-835e-fd6b39331b5d" src="https://user-images.githubusercontent.com/68735863/152641500-c9dceabf-9412-4da1-8c08-62d3b86196e7.png">

# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql

# Screenshots

![Screenshot (360)](https://user-images.githubusercontent.com/68735863/152641421-b05af0c0-ec99-463a-b865-c935741c57f5.png)

![Screenshot (361)](https://user-images.githubusercontent.com/68735863/152641429-6cb9eb11-0f71-4578-9019-fe650fb2dbd4.png)

![Screenshot (362)](https://user-images.githubusercontent.com/68735863/152641431-46ae4f16-78e4-4444-bef3-77827b439262.png)



