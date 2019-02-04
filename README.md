Role Name
=========

Configure a CentOS box for OpenShift 4 running on libvirt.

Based on https://github.com/openshift/installer/blob/master/docs/dev/libvirt-howto.md

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the
role should be mentioned here. For instance, if the role uses the EC2
module, it may be a good idea to mention in this section that the boto
package is required.

Role Variables
--------------

openshift_libvirt_base_domain -- The DNS name for the cluster.

openshift_libvirt_cluster_name -- The name of the cluster.

openshift_libvirt_cluster_ip_range -- The IP address range to be used
by the cluster.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any
details in regards to parameters that may need to be set for other
roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

doug@doughellmann.com