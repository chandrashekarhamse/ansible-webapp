Simple Web Application

STEPS TO RUN

1. Have the ansible setup and select the target nodes.

2. Edit the Host and inventory files according to your hosts

3. Run the playbook using below command.

   ansible-playbook playbook.yml -i inventory.txt
   
4. Access the webpage using any of the nodes IP address 

   Note: if you are running on VM's on AWS open the port 5000 from the security group.
   
   navigate: http://<IP>:5000
             http://<IP>:5000/how%are%you
             
             
             
