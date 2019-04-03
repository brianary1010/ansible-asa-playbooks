# ansible-asa-playbooks
Playbooks for multi context asa

This playbook gathers all contexts configuration files locations and copies the files to location {{ home directory }} (can set in HOSTS vars).
This playbook also copies the system context running configuration, making a complete backup of all configuration files on a multi-context ASA.
At home Directory location a directory named for each ASA host must be created, the playbook will then create a folder with the run date inside that and copy all context configs to that location. 
