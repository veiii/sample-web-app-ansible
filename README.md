
## Automate deployment application with Ansible

This playbook deploy [kodekloudhub/learning-app-ecommerce](https://github.com/kodekloudhub/learning-app-ecommerce) to CentOS 8 server.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/veiii/ansible-sample-web-app.git
   ```
2. Add to /etc/ansible/hosts 
   ```txt
   [centos]
    xx.xx.xxx.xxx ansible_user=centos
   ```
3. Run playbook 
    ```sh
    ansible-playbook deploy.yml
    ``` 

