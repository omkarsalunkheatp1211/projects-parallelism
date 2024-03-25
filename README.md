# Projects Parallelism

1. Introduction

   This project aims to automate the management of Apache HTTP Server (httpd) on web servers using Ansible playbooks. It includes tasks for updating the httpd package to the latest version and removing the Apache HTTP Server.

2. Technology Used

   - Ansible

3. Features

   - Feature 1: Update web server by installing the latest httpd package.
   - Feature 2: Remove Apache HTTP Server from web servers.

4. Usage

   To use this project, follow these steps:
   - Step 1: Ensure Ansible is installed on your system.
   - Step 2: Configure the `ansible.cfg` file as needed.
   - Step 3: Update the `inventory` file with the IP addresses of your managed hosts.
   - Step 4: Execute the playbook for updating the httpd package using the command: `time ansible-playbook playbook.yml`.
   - Step 5: Execute the playbook for removing Apache HTTP Server using the command: `time ansible-playbook remove_apache.yml`.

5. Installation

   To install and set up this project, follow these steps:
   - Step 1: Clone the repository to your local machine.
   - Step 2: Ensure Ansible is installed on your system.
   - Step 3: Configure the `ansible.cfg` file according to your requirements.
   - Step 4: Update the `inventory` file with the IP addresses of your managed hosts.
   - Step 5: You're now ready to use the project as described in the Usage section.
