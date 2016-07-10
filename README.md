Vagrant for Ruby on Rails
============================

BOX
---

    Ubuntu 14.04.4 LTS (GNU/Linux 3.13.0-83-generic i686)
    Ruby 2.3.1p112 (2016-04-26 revision 54768) [i686-linux]
    Rails 5.0.0 (rbenv)
    Node.js v6.2.2
    MySQL 5.5.49 (root|231401)
    PostgreSQL 9.5.3 (root|231401)
    
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
