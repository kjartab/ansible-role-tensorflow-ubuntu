Tensorflow Ubuntu
=========

Currently installs a specific combination which works for my Dell M4800 laptop (Quadro K2100M): Tensorflow 1.4 and CUDA Toolkit 8.0.



Requirements
------------

- NVIDIA CUDA 3.x compatible graphics card
- Download CUDNN (requires login) and put in directory /tmp/libcudnn6_6.0.21-1+cuda8.0_amd64.deb

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: kjartab.tensorflow-ubuntu }

License
-------

MIT

Author Information
------------------

Kjartan Bjørset