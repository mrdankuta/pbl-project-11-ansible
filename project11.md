# Project 11 - Ansible – Automate Project 7 to 10


---

## Step 1 - Install & Configure Ansible
- Rename `jenkins` server name tag from previous projects to `jenkins-ansible` in EC2 and SSH into server.
- Install `Ansible`:
  ```
  sudo apt update
  sudo apt install ansible
  ```
- Check `ansible` version to confirm installation: 
  ```
  ansible --version
  ```
  ![Ansible Installed](images/001-ansible-install.png)
- 