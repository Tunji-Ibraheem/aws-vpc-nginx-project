# AWS Custom VPC + Nginx Project

## What I Built<img width="1366" height="768" alt="vpc-test-security-group" src="https://github.com/user-attachments/assets/7e0b5a69-c90b-49ab-9fff-d3931337a2f6" />
<img width="1366" height="768" alt="live-website-on-server" src="https://github.com/user-attachments/assets/9229bb9c-93b1-40b5-966f-89b998b47e26" />
<img width="1366" height="768" alt="nginx-status-check" src="https://github.com/user-attachments/assets/a5e8aa4d-2bf1-44b2-b8c0-f4d103df8440" />
<img width="1366" height="768" alt="nginx-installed-on-virtual-server" src="https://github.com/user-attachments/assets/1933a48a-5308-483e-9405-15b04edcfb6b" />
<img width="1366" height="768" alt="virtual-server-updated" src="https://github.com/user-attachments/assets/799c394f-1bd0-4e30-b1d4-19f339b947bb" />
<img width="1366" height="768" alt="Amazon-linux-virtual-server" src="https://github.com/user-attachments/assets/cf8dff49-238d-4a46-b719-bc61b4b83c5a" />
<img width="1366" height="768" alt="Elastic-ip-address" src="https://github.com/user-attachments/assets/79bafb25-caf2-49a0-b015-05abb1f84257" />
<img width="1366" height="768" alt="my-vpc-test-server" src="https://github.com/user-attachments/assets/c403346c-6064-4e13-b2b3-2da2aac7f99c" />
<img width="1366" height="768" alt="my-custom-vpc-associated" src="https://github.com/user-attachments/assets/4a5e8e25-bcf1-4b50-85dd-df7d91f38a8a" />
<img width="1366" height="768" alt="my-private-subnet" src="https://github.com/user-attachments/assets/f1793926-d918-4ace-8d87-7344c08c96f1" />
<img width="1366" height="768" alt="my-public-subnet" src="https://github.com/user-attachments/assets/ada94643-99d0-4096-867a-78d700d123f4" />
<img width="1366" height="768" alt="my-cutom-vpc" src="https://github.com/user-attachments/assets/63ca65fc-ef73-491c-8197-87639eb91253" />

Deployed a live Nginx web server on AWS EC2
inside a custom VPC built from scratch.

## Architecture
- Custom VPC (10.0.0.0/16)
- Public Subnet (10.0.1.0/24)
- Private Subnet (10.0.2.0/24)
- Internet Gateway
- Route Tables
- EC2 instance running Nginx
- Elastic IP for permanent address
- Security Groups

## Services Used
Amazon VPC, EC2, Elastic IP, 
Security Groups, Nginx

## Steps I Followed
1. Created custom VPC
2. Created public and private subnets
3. Attached Internet Gateway
4. Configured Route Tables
5. Launched EC2 in public subnet
6. Allocated and attached Elastic IP
7. SSH'd into server
8. Installed and configured Nginx
