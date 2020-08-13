# ansible_anthos
Ansible playbooks to install kvm, pxe server, vmware and anthos


============================
Key Based Authentication
============================

1. Create SSH Key on Ansible Host
    
    ssh-keygen
 
    ~/.ssh/id_rsa.pub

2. Copy Key file to SSH Server (KVM Host)

    ssh-copy-id root@<centos7_machine_ip>
============================


============================
Install Python packages on Ansible Host -
============================

pip install lxml

pip install PyVmomi

pip install jmespath 

============================

123