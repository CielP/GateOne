# GateOne
```
yum install -y epel-release
yum install -y python-pip
yum install -y git
yum clean all
pip install --upgrade pip
pip install tornado==4.5.3
pip install --upgrade setuptools
pip install html5lib
pip install Pillow

yum install -y python python-pip gcc python-devel setuptool python-pam openssl openssl-devel wget make gcc-c++ patch pam_radius dtach pyOpenSSL perl

pip install kerberos

git clone https://github.com/liftoff/GateOne.git
cd GateOne
python setup.py install

nodup gateone > /dev/null 2>&1 &

```
