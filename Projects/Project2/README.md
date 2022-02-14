## Part 1 - Build a VPC

1. Create a VPC.
   ![vpc screenshot](Images/VPC_Screenshot.PNG)
   - A VPC is a virtual network dedicated to your aws account
2. Create a subnet
   ![vpc screenshot](Images/Subnet_Screenshot.PNG)
   - A subnet is a range of ip addresses in the vpc
3. Create an internet gateway
   ![vpc screenshot](Images/Gateway_Screenshot.PNG)
   - An internet gateway is a computer that routes traffic from you private network to outside your network
4. Create a route table
   ![vpc screenshot](Images/RouteTable_Screenshot.PNG)
   - A routing table has ruled dictating where to direct your network traffic
5. Create a security group
   - Tag it with "YOURLASTNAME-sg"
   - Allow SSH for a set of trusted networks including:
     - Your home / where you usually connect to your instances from
     - Wright State (addresses starting with 130.108)
     - Instances within the VPC
   - Attach it to your VPC
   - Image should include your Inbound rules
6. (If necessary, else skip) Create a key pair
