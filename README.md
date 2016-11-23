Role Name
=========

Papertrail can utilize rsyslog and it's go utility remote_syslog2. This role configures and deploys all the neccessary bits to utilize Papertrail on EL7 systems

Requirements
------------

rsyslog is an obvious requirement that should be installed in most EL7 systems

Role Variables
--------------

papertrail_version is the version number of the remote_syslog tool you wish to use.
papertrail_files is an array of absolute paths to logs you want remote_syslog to send to the Papertrail service
papertrail_host is the hostname provided by Papertrail for your use
papertrail_port is the port number provided by Papertrail for your use

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - papertrail

License
-------

MIT/BSD

Author Information
------------------

Chris Short
https://chrisshort.net
