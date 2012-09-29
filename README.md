https://github.com/res0nat0r/gitosis.git
apt-get install git gitcore openssh-server openssh-client
apt-get install python python-setuptools
useradd -m git
passwd git

git clone git@eagin.net/gitosis.git
python setup.py install

git clone git@localhost:gitosis-admin.git
######gitosis.conf 
######/keydir/abc.pub


