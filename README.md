This Project regards the Fourth Class Assignment (CA) of the DevOps discipline at the **.SWitCH() - Postgraduate in Software Development @ Instituto Superior de Engenharia do Porto, 2020/2021 edition**.

For this CA, the task was to use Containerization recurring to **Docker**.

In the first part of the Assignment the purpose was replicating the solution used in the Third Class Assignment (Virtualization tutorial), but this time using Docker Containers.

The _Part1_ folder contains the steps regarding the containerization of the Gradle Basic Demo Application in two containers:  
    - A _Web_ container (with Tomcat to run the Spring application).  
    - A _DB_ container (to execute the H2 server database).

It also includes the publishing of those docker images to Docker Hub.


The _Part2_ folder regards the usage of **Heroku** as a way to deploy our containers into the cloud. 


Both folders have a detailed Readme representing the tutorial for each of the parts.