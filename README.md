software_gcloud
=========

This role will install software_gcloud software

Requirements
------------

All dependencies will appear on requirements.yml file

Role Variables
--------------

software_packages:
  - google-cloud-sdk
  - google-cloud-sdk-app-engine-grpc
  - google-cloud-sdk-pubsub-emulator
  - google-cloud-sdk-app-engine-go
  - google-cloud-sdk-cloud-build-local
  - google-cloud-sdk-datastore-emulator
  - google-cloud-sdk-app-engine-python
  - google-cloud-sdk-cbt
  - google-cloud-sdk-bigtable-emulator
  - google-cloud-sdk-app-engine-python-extras
  - google-cloud-sdk-datalab
  - google-cloud-sdk-app-engine-java


repo_url: 'deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main' # chrome repository
repo_key: 'https://dl-ssl.google.com/linux/linux_signing_key.pub' # chrome key

Not defined yet. But in the future we could stage software version in here

Dependencies
------------

All dependencies will appear on requirements.yml file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xussof.software_gcloud }

License
-------

BSD

Author Information
------------------
Made by @xussof
