# Image_factory_linux_playbooks

# Description:

Through packer provisioner 
- perform image hardening as per worldpay security standards
- install agents while creating template

# Required inputs 
  - env_input: ['lab','stage1','edpc']
  - os_input: ['rhel','centos','rhel',windows]
  - version_input: ['7','core_1809','core_2016','core_2019','desktop_2016','desktop_2019']
  - hypervisor: ['vsphere','openstack']
  - vm_name: "string" | optional   # name of template(from which image is build) to be set under /etc/ansible/facts.d/gold_image.fact
  
