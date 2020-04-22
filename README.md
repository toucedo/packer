# packer

Ansible-Deploy:
/tools/ansible-deploy-vmware-vm$ ansible-playbook -i vms-to-deploy deploy-kubernetes-prod.yml


Packer Create Template:
/tools/packer-vsphere-builds/debian-10$ packer build -var-file variables.json.sample debian-10.json
