# ansible-asa-playbooks
Playbooks for multi context asa

This playbook gathers all contexts configuration files locations and copies the files to location {{ home directory }} (can set in HOSTS vars).
This playbook also copies the system context running configuration, making a complete backup of all configuration files on a multi-context ASA.
