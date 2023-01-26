# ansible_study_lab_solution
To install ansible via WSL2 on Windows machine
- Run Powershell as an administrator and type in the following command
- `wsl --install`
- restart the workstation
- open Ubuntu app and run the following in the terminal
- `sudo su`
- `apt-get update`
- `apt-get install ansible`

To run the solution playbook
- `cd ansible_lab`
- update server IPs or domain names in "inventory" file
- `ansible-playbook --ask-become-pass study_solution.yml`
