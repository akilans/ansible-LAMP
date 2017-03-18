# This is ansible playbook for installing LAMP

# Install Ansible in your machine

# Add target machine IP address in hostfile [Replace 192.168.33.12 with your web server IP address ]

# Enable SSH connection between your machine to target machine

# Execute ansible task for Installing LAMP by calling the command "ansible-playbook -i hosts site.yaml" 




############################################################################
                     NOTE
############################################################################

# To practice ansible in your local environment vagrant & virtualbox is very good

#SSH CONFIG TUTORIAL

---> Install openssh-server in target machine

From Host machine,

---> Run "ssh-keygen" to generate RSA key pair & note down the location
---> Run "ssh-copy-id -i /home/akilan/.ssh/id_rsa vagrant@192.168.33.12" command to copy RSA key pair to the target machine


##############**That's It**#################################################
