This yml file consists of tasks  required to deploy apache web application which runs on 172.168.10.0/30 network on a remote server.
The tasks include:
Update apt cache and install necessary packages
Add Docker GPG key
Add Docker repository
Install Docker
Install Docker Compose
Create Docker network
Start Apache container

Instructions to install this ansible playbook:
at the terminal of controller machine, execute the below command to clone the repository
git clone https://github.com/DonaM12/ca1.git
