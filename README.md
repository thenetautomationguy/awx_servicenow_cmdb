# Ansible ServiceNOW CMDB

## Description
For individuals who opt not to maintain a static Ansible inventory file and are already leveraging a well-established Configuration Management Database (CMDB) in ServiceNow, an integration as a dynamic inventory within AWX is feasible. This setup allows for enhanced flexibility, including the ability to filter CMDB entries using filter_results and create Ansible host groups with keyed_groups.

Regarding access credentials for ServiceNow, there are two main approaches: they can be either directly hard-coded in the inventory YML file for simplicity or, for added security, provided via the AWX Credentials Vault. For detailed instructions, refer to the instruction.txt file.

## Important Note
Ensure that your filename always ends with the *now.yml extension. 