Ansible Role: osm
=========

https://github.com/Overv/openstreetmap-tile-server.git



Example Playbook
----------------

    - hosts: servers
      vars:
        pbf_url: 'http://download.geofabrik.de/russia-latest.osm.pbf'
      roles:
         - aemelyanenko.osm

License
-------

BSD
