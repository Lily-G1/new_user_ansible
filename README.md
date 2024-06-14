# Add a new user to linux server 
This ansible play lets new members of our dev team enter their user details and SSH public keys.  
When the playbook is run, it adds these users to our existing dev EC2 instance, giving them SSH access and sudo privileges to administrative members  

## To use:
- Fork repository
- Create a new branch  
- Enter your user details in the group_vars/all/dev_team.yml file using the same template  
- Non administrative team members should leave the 'admin' field blank
- Create & send a pull request for reviews and merges  
