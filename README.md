# how-to-integrate-ssh-git
This page explains how to integrate ssh to github and basic git hub commands

# Integrate ssh to git
cd ~  
  This commands will take you to root directory  
  
ssh-keygen  

  This commands will create rsa key for machine(laptop)  
  
press enter 4 times  

go to powershell (run as admin)

cd ~  

cd .ssh  

 Get-Service -Name ssh-agent | Set-Service -StartupType Automatic  

  Start-Service ssh-agent  

  ssh-add id_rsa  

  
 
 










