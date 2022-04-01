AMI of Maven,Tomcat and Nginx Instances
It has  two vpc's
*App vpc
*Batison Vpc
It Has SUbnet in Oregon us-west-1
*Pair of public and private subnet in us-west-1a
*pair of public and private subnet in us-west-1b
Configured them with the routetables accordlingly
Made launch Configuration for launching the Instances
After Launch of the instances,
Created an Autoscaling group for private subnets where my app servers are running
Created an sutoscaling group for public subnets where my nginx server are running
created an Internal Network load balancer for Private Servers
Created an Internet facing Network Load Balancer for nginx server
Accessed the Private servers with the batison Host
Able to view the tomcat login app running by using the Network load balancer DNS.
Created an MYSQL DB
Connected the DB using SSH from my Local Ip
Created an Secuirty group for allowing my private server ip's
verified the flow of data from the webpage and DB.
