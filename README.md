# Application Deployment Demo
Demonstrate different application deployment strategies inside OCP
1. Application DockerImage
2. Dockerfile on Git
3. Source (Builderimage+Git)
4. Predefined templates 
5. Webconsole (UI)

**Process Flow**
OCP client

**Dockerimage** ---> Push to Integrated Docker Registry ---> Image-Stream --->
Deployment Config ---> Replication Controller --- **Application POD**     

**Dockerfile** --- > Build Config ---> **Application Dockerimage** ---> Push to Integrated Docker Registry ---> Image-Stream ---> Deployment Config ---> Replication Controller --- **Application POD** 

**Source** --- > **Builder_Docker_Image** Build Config ---> **Application Dockerimage** ---> Push to Integrated Docker Registry ---> Image-Stream ---> Deployment Config ---> Replication Controller --- **Application POD**     



