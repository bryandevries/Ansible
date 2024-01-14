# Ansible
Repo for Ansible learning

[Module Examples]
ansible linux -m ping
ansible linux -a "cat /etc/os-release"
ansible linux -m gather_facts -k

[Playbook Examples]
ansible-playbook neofetch.yml -K -k
