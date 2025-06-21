# linux-foundamentals-vagrant
Kodecamp Task 2
# Set Up a Vagrant Server
Screenshot #1: Vagrant initialization and SSH login
![Screenshot (22)](https://github.com/user-attachments/assets/814345d2-debe-4ab6-97b8-3f028451dae1)
![Screenshot (21)](https://github.com/user-attachments/assets/aa396a9e-8514-474b-9861-e3d06b6caed8)
__Description:__ I initialized a new Vagrant environment using the generic/alpine318 box with vagrant init generic/alpine318. To optimize performance on my low-memory PC, I updated the Vagrantfile to allocate only 1 CPU and 128MB of RAM. After running vagrant up, I successfully booted the virtual machine and accessed it via SSH. The prompt confirms I am inside the VM at the /home/vagrant directory.

# Explore the Linux File System
Screenshot #2: Custom folder structure created
![Screenshot (25)](https://github.com/user-attachments/assets/8cbed2dd-951b-4df9-a1cc-1a81f4d081be)
__Description:__ Inside the VM home directory (/home/vagrant), I created a custom folder structure using mkdir. The structure includes a projects directory, which contains a subdirectory named devops. This helps organize development work and separates different project types or environments under clearly labeled folders.


![Screenshot (27)](https://github.com/user-attachments/assets/21c278c3-dad7-4734-b85c-ac1e60ff8eb7)
![Screenshot (26)](https://github.com/user-attachments/assets/dd5ff685-cc38-4e5d-808d-3634cd9c88e4)
![Screenshot (25)](https://github.com/user-attachments/assets/8cbed2dd-951b-4df9-a1cc-1a81f4d081be)
![Screenshot (24)](https://github.com/user-attachments/assets/3d202aa0-31a7-411c-a1af-7dbdc0b09368)
![Screenshot (28)](https://github.com/user-attachments/assets/6949dd9e-fbb9-4acf-bbec-3a735e8cc694)
