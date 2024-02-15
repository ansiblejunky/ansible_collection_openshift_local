# Ansible Collection - ansiblejunky.openshift_local

Ansible Collection to manage OpenShift Local instance.

## Requirements

None

## Using

Install the collection and then run the playbooks from anywhere.

```shell
# Install collection into your collection path
git clone git@github.com:ansiblejunky/ansible_collection_openshift_local.git

# Prepare crc
ansible-playbook ansiblejunky.openshift_local.prepare
# Start crc
ansible-playbook ansiblejunky.openshift_local.start
# Check status
ansible-playbook ansiblejunky.openshift_local.status

... do cool things ...

# Stop crc
ansible-playbook ansiblejunky.openshift_local.stop
# Delete crc
ansible-playbook ansiblejunky.openshift_local.delete

```

## License

GPLv3

## Author

John Wadleigh