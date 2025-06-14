Step 1: Created a VPC (my-vpc) with public and private subnets.
Step 2: Set up an Internet Gateway (my-igw).
Step 3: Verified subnets.
Step 4: Configured public and private Route Tables.
Step 5: Set up Security Groups (public-sg and private-sg).
Step 6: Launched VM0 in a private subnet (us-east-1a, IP: 10.0.131.180).
Step 7: Launched VM1 in a public subnet (us-east-1a, public IP: 3.88.237.26, private IP: 10.0.5.70).
Step 8: Generated a 1GB demo.txt file in VM1 using a C++ program.
Step 9: Copied demo.txt from VM1 to VM0 and deleted it from VM1.
Step 10: Created an auth.sh script in VM1, retrieved demo.txt from VM0 to VM1 with authentication.
Step 11: Launched VM2, copied demo.txt to VM2, and deleted it from VM1 (you just did this!).
