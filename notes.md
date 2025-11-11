i stance name = prod-instance

key pair name = prod-key-pair


=> ngnix is used for frontend 

=> public dns is main domain , so we connect instance 


=> nano .env

Press Ctrl + O → then press Enter to save.
Press Ctrl + X to exit Nano.

=> chmod 400 "Prod.pem"

=> 
=> ssh -i "Prod.pem" ubuntu@ec2-3-27-116-216.ap-southeast-2.compute.amazonaws.com

after this run cmd cd backend-runner

=>Runner = a temporary computer that executes your workflow (like build, test, or deploy).
