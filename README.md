# Set-up Local

Created: February 16, 2022 9:01 PM
Last Edited Time: March 13, 2022 4:08 PM

# Overview
This project is composed of two ansible playbooks that set up a fedora workstation with some of the most used tools for programming (containers, interpreters and compilers, testing tools, database management and more) and other basic usage like media. 

The script that runs the playbook locally is `ansible-playbook fedora-base.yml --ask-become-pass --ask-pass`, first run the base playbook and then the apps playbook. The base playbook must be run first.
