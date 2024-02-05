# Configure zones and zoneset to Cisco MDS fabrics with Ansible
Pushes zones and zoneset to Cisco MDS fabrics via Ansible

Looping over a list of wwns is too slow and resource consuming for the MDS fabrics, so one need to create a list of members and zone members and push those lists to fabrics.
