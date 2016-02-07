Info

ubuntu/trusty32
ruby 2.2.3p173 (2015-08-18 revision 51636) [i686-linux]
rails 4.2.5
nodejs
MySQL 5.5.47 (root|root)
PostgreSQL 9.3.10 (root|root)

Configuring Git

git config --global color.ui true
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR@EMAIL.com"
ssh-keygen -t rsa -C "YOUR@EMAIL.com"

cat ~/.ssh/id_rsa.pub

ssh -T git@github.com
