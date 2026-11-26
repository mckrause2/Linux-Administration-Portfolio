# Remote Linux Administration with Ansible and Termux

### Project Overview

This project documents the configuration and implementation of a remote Linux administration environment using an Android mobile device running Termux as an Ansible control node.

I configured secure SSH key-based authentication and used Ansible to remotely administer two Rocky Linux servers. I also developed Bash scripts to automate the execution of Ansible playbooks and ad hoc commands.

## Project Objectives

- Establish secure remote access to two Rocky Linux servers.
- Configure Ansible to manage multiple Linux systems from a centralized control node.
- Use Ansible playbooks and ad hoc commands to perform administrative tasks.
- Develop Bash scripts to simplify and automate routine server administration.

## Implementation Approach

- Configured Termux on an Android mobile device as the Ansible control environment.
- Established SSH key-based authentication between the control device and both Rocky Linux servers.
- Created an Ansible inventory containing both managed servers.
- Developed and executed Ansible playbooks for remote administration.
- Used Ansible ad hoc commands to perform individual administrative operations.
- Created Bash scripts to automate the execution of playbooks and ad hoc commands.
- Executed routine administrative tasks, including system updates and shutdown operations, across both servers.

## Skills Demonstrated

- Linux system administration
- Remote Linux server administration
- SSH and key-based authentication
- Ansible configuration and inventory management
- Ansible playbook development and execution
- Ansible ad hoc commands
- Bash scripting and automation
- Multi-server administration
- Remote system maintenance
- Mobile-based Linux administration

## Technical Documentation

For the detailed configuration process, commands, Bash scripts, and explanations, see:

[Open the Jupyter Notebook]()

## Environment

- **Control Device:** Android mobile device
- **Administration Environment:** Termux
- **Managed Operating Systems:** Rocky Linux
- **Remote Access:** SSH, SSH key-based authentication
- **Configuration Management:** Ansible
- **Automation:** Bash scripting
- **Administrative Operations:** System updates and shutdown operations
- **Managed Infrastructure:** Two Rocky Linux servers
