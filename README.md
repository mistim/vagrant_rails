Vagrant for Ruby on Rails
============================

BOX
---

    Ubuntu 14.04.3 LTS (GNU/Linux 3.13.0-77-generic i686)
    Ruby 2.2.3p173 (2015-08-18 revision 51636) [i686-linux]
    Rails 4.2.5
    Node.js v4.2.6
    MySQL 5.5.47 (root|root)
    PostgreSQL 9.3.10 (root|root)
    
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
