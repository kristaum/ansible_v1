# ansible_v1
Projetct to install tomcat, configure, deploy and makes sure its up. 
<br>This sample will do that in one node(local) with centos 7
<br>
<br>On install_tomcat.yml we provide the necessary vars to install any desired jdk and tomcat compatible with centos 7.
<br>We are also providing the user and the group who will be the owner of tomcat, preferably not root user.
<br>
<br>
<br> On deploy_tomcat.yml we are providing the war file location on machine which will be copied to node server. We also set user and group that will perform operation.
<br>
<br> This project was just my first hands on with ansible.
