System Configuration Playbook

Role Name
=========

Role name is system as mentioned task readme file

Requirements
------------

Anslibe, AWS EC2


### Purpose
This playbook automates the setup of a basic system configuration, including firewall setup, system parameter adjustment, and package installation.

## Tasks Overview
Install UFW (Uncomplicated Firewall): Installs the UFW package, I have used simple and user-friendly firewall for Linux systems.
Allow OpenSSH: Opens port 22 for incoming SSH traffic, allowing remote access to the system.
Allow HTTP: Opens port 80 for incoming HTTP traffic, typically used for web server communication.
Allow HTTPS: Opens port 443 for incoming HTTPS traffic, used for secure web server communication.
Deny all other ports: Blocks all incoming traffic on ports not explicitly allowed, enhancing security by default.
Enable UFW: Activates the UFW firewall to enforce the configured rules and protect the system.
Set vm.swappiness to 10: Adjusts the system's swappiness parameter to 10, optimizing memory management.
Install htop: Installs the htop package, a command-line utility for system monitoring and management.