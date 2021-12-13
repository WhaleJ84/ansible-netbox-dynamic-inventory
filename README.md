# ansible-netbox-dynamic-inventory

This repository is used in Ansible AWX to dynamically source an inventory from Netbox.
Uses the following [Netbox](https://docs.ansible.com/ansible/latest/collections/netbox/netbox/nb_inventory_inventory.html) module for Ansible to interact with the Netbox API.

## Variables

Pass these variables through by adding them to the source variables for the inventory.

| Variable     | Description                                                        |
| ------------ | ------------------------------------------------------------------ |
| NETBOX_API   | The URL for the Netbox instance (e.g. `http://netbox.example.com`) |
| NETBOX_TOKEN | The token for the API endpoints                                    |
