prequisites: 
- ansibe 
- ssh 
  
dd your raspbian image onto your pi and install ssh.
once you have that
to set up your raspberrypi run:

ansible-playbook -i ip-of-your-pi, -u pi -k
