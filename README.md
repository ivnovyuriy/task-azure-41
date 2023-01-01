
# AZURE task 4.1

1. You plan to create Virtual network with 2 subnets subnetbe01 and subnetfe01. 
- You need 3 Ubuntu-based virtual machines VMLUE01, VMLU01, VMLU02.
- VMLUE01 should have 2 Network interfaces. NICfe01 should be created in subnetfront01, NICbe01 should be in subnetbe01
- VMLU01 and VMLU02 should be in subnetbe01
- VM in subnetfe01 should have access to the internet, VMs in subnetbe01 should be accessible and exchange data only with VMLUE01

![infra](https://github.com/ivnovyuriy/task-azure-41/blob/c52d8c87dbfddf00a2250e5e26ea4f15f57cc508/img/insfra.png)

![login](https://github.com/ivnovyuriy/task-azure-41/blob/c52d8c87dbfddf00a2250e5e26ea4f15f57cc508/img/login_VMLUE.png)

![backend_rules](https://github.com/ivnovyuriy/task-azure-41/blob/c52d8c87dbfddf00a2250e5e26ea4f15f57cc508/img/backend_rules.png)

2. (Advanced) Install ansible on VMLUE01. Run any commands or install packages through ansible on VMLU01 and VMLU02

![ansible](https://github.com/ivnovyuriy/task-azure-41/blob/c52d8c87dbfddf00a2250e5e26ea4f15f57cc508/img/ansible.png)

3. (Advanced) Install docker on VMLUE01 and configure FTP server based on any image.

![docker-ftp](https://github.com/ivnovyuriy/task-azure-41/blob/c52d8c87dbfddf00a2250e5e26ea4f15f57cc508/img/docker-ftp.png)

![ftp](https://github.com/ivnovyuriy/task-azure-41/blob/c52d8c87dbfddf00a2250e5e26ea4f15f57cc508/img/ftp.png)

![ftp_get_file](https://github.com/ivnovyuriy/task-azure-41/blob/c52d8c87dbfddf00a2250e5e26ea4f15f57cc508/img/ftp_get_file.png)

4.  ** You need to automate tasks utilising IaaC tools of your choice (For e.g. Terraform).

![tfstatelist](https://github.com/ivnovyuriy/task-azure-41/blob/c52d8c87dbfddf00a2250e5e26ea4f15f57cc508/img/tfstatelist.png)
