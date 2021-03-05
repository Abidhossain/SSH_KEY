# Generating a new SSH Key
`ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`

# Adding SSH key to the ssh-agent
1. Start the ssh-agent in the background: 
``eval `ssh-agent -s``

2. Add SSH private key to the ssh-agent: `ssh-add ~/.ssh/private_key_file`