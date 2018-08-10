# ansible-playbooks
These playbooks are designed to provide to the user a better way to manage their OpenStack resources

# requirements


   - The standard OpenStack environment variables, such as OS_USERNAME may be used instead of providing explicit values.
   - Auth information is driven by os-client-config, which means that values can come from a yaml config file in /etc/ansible/openstack.yaml, /etc/openstack/clouds.yaml or ~/.config/openstack/clouds.yaml, then from standard environment variables, then finally by explicit parameters in plays. More information can be found at http://docs.openstack.org/developer/os-client-config

   
   - openstacksdk
   - python >= 2.7



