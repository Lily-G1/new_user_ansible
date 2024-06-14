# Create EC2 instance    
Dynamically create and delete EC2 instances on AWS using create_ec2.yml, delete_ec2.yml and aws_ec2.yml  

# Add a new user to EC2 linux server  
This ansible play lets new members of our dev team enter their user details and SSH public keys.  
When the playbook is run, it adds these users to our existing dev EC2 instance, giving them SSH access and sudo privileges to administrative members  

## To use:
- Fork repository and create a new branch  
- Navigate to group_vars/all/dev_team.yml. Copy template, paste at bottom and edit with your details   
- Non administrative team members should enter 'non-admin' as value to 'type'
- Create a pull request for review and merging    
