# ansible_tasks


 # checks the syntax of the playbook 
ansible-playbook <name> --syntax-check
  
  # does a dry run, reports the will-be changes, but the playbook is not executed  
ansible-playbook <name> --check 
  
   # ask to confirm each-step
ansible-playbook <name> --step
