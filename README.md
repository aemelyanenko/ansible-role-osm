Ansible Role: osm
=========

https://github.com/Overv/openstreetmap-tile-server.git


Example Playbook
----------------

    - hosts: servers
      vars:
        pbf_url: 'http://download.geofabrik.de/russia/south-fed-district-latest.osm.pbf'
        pip_install_packages: docker
      roles:
        - geerlingguy.pip
        - geerlingguy.docker
        - aemelyanenko.osm

License
-------

BSD
