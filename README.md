# linux-foundamentals-vagrant
Kodecamp Task 2
# Set Up a Vagrant Server
__Screenshot #1:__ Vagrant initialization and SSH login

![Screenshot (22)](https://github.com/user-attachments/assets/814345d2-debe-4ab6-97b8-3f028451dae1)
![Screenshot (21)](https://github.com/user-attachments/assets/aa396a9e-8514-474b-9861-e3d06b6caed8)

__Description:__ I initialized a new Vagrant environment using the generic/alpine318 box with vagrant init generic/alpine318. To optimize performance on my low-memory PC, I updated the Vagrantfile to allocate only 1 CPU and 128MB of RAM. After running vagrant up, I successfully booted the virtual machine and accessed it via SSH. The prompt confirms I am inside the VM at the /home/vagrant directory.

# Explore the Linux File System

__Screenshot #2:__ Custom folder structure created

![Screenshot (25)](https://github.com/user-attachments/assets/8cbed2dd-951b-4df9-a1cc-1a81f4d081be)
__Description:__ Inside the VM home directory (/home/vagrant), I created a custom folder structure using mkdir. The structure includes a projects directory, which contains a subdirectory named devops. This helps organize development work and separates different project types or environments under clearly labeled folders.

# Manage File Permissions and Ownership
__Screenshot #3a:__ File permission change

![Screenshot (29)](https://github.com/user-attachments/assets/6b245dbc-1b35-419e-8399-7cc8e91bd8db)

# Install and Configure a Package
__Screenshot #4:__ Package installation and version check

![Screenshot (26)](https://github.com/user-attachments/assets/dd5ff685-cc38-4e5d-808d-3634cd9c88e4)
__Description:__ I installed the curl utility using Alpine’s package manager with the command sudo apk add curl. After the installation, I verified the installed version using curl --version, which confirmed that version 8.5.0 was successfully installed.

# Test Remote Connectivity
__Screenshot #5:__ Ping result

![Screenshot (27)](https://github.com/user-attachments/assets/21c278c3-dad7-4734-b85c-ac1e60ff8eb7)
![Screenshot (28)](https://github.com/user-attachments/assets/6949dd9e-fbb9-4acf-bbec-3a735e8cc694)

__Description:__ I used the ping command with -c 4 to send four ICMP echo requests to google.com. The result shows successful communication with 0% packet loss and a round-trip average time of approximately 52 ms.

This confirms that the virtual machine has active internet access, and the network connection is functioning properly — a crucial step before performing updates, downloading packages, or configuring remote tools.
