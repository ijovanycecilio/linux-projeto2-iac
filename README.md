# linux-projeto2-iac
Script para provisionamento de um servidor Apache (projeto integrante do curso de Linux da DIO)

# Infrastructure as Code:
# Apache Web Server Provisioning Script

Infrastructure as Code (IaC) is the practice of managing and provisioning infrastructure through code, rather than manual processes.
With IaC, configuration files are created that include the specifications of your infrastructure, making it easier to edit and distribute configurations. 
It also ensures consistent provisioning of the same environment every time.

Link: Red Hat - https://www.redhat.com/

# Version control

Version control is an important part of IaC. Configuration files should be treated as source code, just like any other software source code.
When deploying infrastructure as code, it is also possible to break it down into modules, which can be combined in different ways through automation.

# Definitions

  Restore the previously created snapshot in VirtualBox;
  
  Update the server;
  
  Install Apache2;
  
  Install unzip;
  
  Download the application available at https://github.com/denilsonbonatti/linux-site-dio/archive/refs/heads/main.zip to the /tmp directory;
  
  Copy the application files to the default Apache directory;
  
  Upload the script file to a repository on GitHub.
