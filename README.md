# gitlab_cicd_example

This is a Gitlab pipeline example with ansible.
Compile a.py and b.py to binary. and deploy as a service on production server

You need a :
  - Gitlab server : Require python   
  - Build server  : Require librarys in requirement.txt
  - Test server
  - Deploy Server : Require ansible and sshpass
  - Production Server

![image](https://user-images.githubusercontent.com/4043666/225212071-8c1c1a99-f9b5-4e7f-8df8-7a554ea1ce25.png)


The Process Step is :
1. Build a.py and b.y to binary

2. Test the binary is work

3. Deploy the service to staging server

4. Deploy the service to production server
