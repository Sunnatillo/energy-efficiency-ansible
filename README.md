# energy-efficiency-ansible
Modify the tas_dir and power_dir variables in both ansible playbooks and run following:

1. ANSIBLE_FORCE_COLOR=true ansible-playbook tas.yaml --ask-become-pass -v
2. ANSIBLE_FORCE_COLOR=true ansible-playbook power-driven-scheduling.yaml -v