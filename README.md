Vagrant for Ruby on Rails
============================

BOX
---

    Ubuntu 14.04.4 LTS (GNU/Linux 3.13.0-83-generic i686)
    2.3.0p0 (2015-12-25 revision 53290) [i686-linux]
    Rails 5.0.0.beta3 (rbenv)
    Node.js v5.9.0
    MySQL 5.5.47-0ubuntu0.14.04.1 (root|root)
    PostgreSQL 9.3.11 (root|root)
    Redis server v=2.8.4 sha=00000000:0 malloc=jemalloc-3.4.1 bits=32 build=8f6097d7914679ca
    
SSH
---

    Host 127.0.0.1
    Port 2222
    User vagrant
    Password vagrant

Configuring Git
---------------

    git config --global color.ui true
    git config --global user.name "YOUR NAME"
    git config --global user.email "YOUR@EMAIL.com"
    ssh-keygen -t rsa -C "YOUR@EMAIL.com"

    cat ~/.ssh/id_rsa.pub

    ssh -T git@github.com
