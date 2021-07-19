# K8s-Wordpress-Mysql-Ansible
Configuring K8s Cluster ,Wordpress or Master and Exposing the Wordpress pod using Ansible

<h2>Here I configure the kubernetes cluster on the aws also launch the wordpress and mysql database and exposed that pod using Ansible. </h2>

<h3>Technology used </h3>

<img src="/image/jjji.gif" width="300" height="150">  <img src="/image/mysql.gif" width="200" height="150">

<img src="/images/www.gif" width="300" height="150">  <img src="/images/aws.gif" width="300" height="150">  

<h4>File Require</h4>
1.In This we Require the .pem file to login to IAM.

<h3>Software require</h3>
 1. Ansible.

 2. boto.

 3. boto3 ,ec2
 
 In this we use dynamic inventory update approach so we dont require to add ip of Master and slave inventory it will directly add in the Inventory\
 
 
 Also in this we used the Wordpress so please check the cidr range given whether it is matching with flannel in k8s cluster if not then change it accordingly in my case i change it to 10.244.0.0 check before lauching because of this we are unable to connect wordpress to our Database
 
 <h2>Hopeyou like it </h2.
 <h2>Thank you !!!😊😊😊</h2>
