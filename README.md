# DevNet-DNA-Lab-Setup

A collection of Ansible playbooks to setup Cisco dCloud DNA Express 3.0 sandbox to run guestshell (and Python) on CSR routers in the sandbox.

Download this repository to the CentOS box in the sandbox and run the following commands to setup the CSRs:

    ansible-playbook -i inventory csr_vpg_setup.yaml
    ansible-playbook -i inventory csr_guestshell_setup.yaml
  
