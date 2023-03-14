# gitlab_cicd_example

This is a Gitlab pipeline example with ansible.


You need a :
  - Gitlab server : Require python   
  - Build server  : Require librarys in requirement.txt
  - Test server
  - Deploy Server : Require ansible and sshpass
  - Production Server



The Process Step is :
1. Build a.py and b.y to binary

2. Test the binary is work

3. Deploy the service to staging server

4. Deploy the service to production server
