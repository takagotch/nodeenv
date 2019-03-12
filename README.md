### nodeenv
---
https://github.com/ekalinin/nodeenv

```
```

```
sudo easy_install nodeenv
sudo pip install nodeenv

ln -s debian-upstream debian
dpkg-buildpackage -uc -us -b
sudo dpkg -i $(ls -1rt ../nodenv_*.deb | tail -nl)

virtualenv env
. env/bin/activate
pip install nodeenv
nodeenv --version

git clone https://github.com/ekalinin/nodeenv.git
./nodeenv/nodeenv.py --help
nodeenv env
. env/bin/activate
node -v
npm -v
deactivate_node
nodeenv --without-ssl --node-0.4.3 --npm-0.3.17 --jobs=4 env=4.3

nodeenv --node=0.10.25 --source env-0.10.25
time nodeenv --node=0.19.25 --prebuilt env-0.10.25-prebuilt
time nodeenv --node=0.10.25 --source env-0.10.25-src

nodeenv --node=system

. env-4.3/bin/activate
npm install -g express
npm install -g jade
freeze ../prod-requirements.txt

freeze -l ../prod-requirements.txt
nodeenv --requirements=../prod-requirements.txt --job=4 env-copy
cat ../prod-requirements.txt
mkvirtualenv my_env
. my_env/bin/activate

nodeenv -p

nodeenv -m /usr/local/bin/gmake ENV
workon my_env
npm install -g coffee-script
which coffee

nodeenv --requirements=requirements.txt --jobs=4 --force env
. env-4.3/bin/activate
./env-4.3/bin/shim --version

virtualenv env
. env/bin/ctivate
nodeenv --iojs --list
nodeenv --iojs -p --prebuilt
```

```
```


