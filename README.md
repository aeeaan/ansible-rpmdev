correcthorse.rpmdev
=========

A role for maintaining and documenting the build environment for the packages kept in correcthorse packagecloud rpm repo. It creates a build user and a separate user for using packagecloud.io

Role Variables
--------------
| Variable			| Default			| Notes			|
| :---				| :---				| :---			|
| rpmdev_build_user		| build				| 			|
| rpmdev_package_user		| package			|			|

Dependencies
------------

correcthorse.common

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.rpmdev }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
