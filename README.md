# CloudKi modules

default modules for the cloudKi Client Software Suite



```bash
# to build
# from root
git submodule add -b master https://github.com/jasenmichael/cloudKi-modules modules
# from modules
git submodule add -b master https://github.com/jasenmichael/cloudKi-static-server-module static-server
git submodule add -b master https://github.com/jasenmichael/pm2-ui pm2-ui
git submodule add -b master https://github.com/jasenmichael/cloudKi-cloud-client-module cloud-client
cd static-server
git pull origin master
cd ../pm2-ui
git pull origin master
cd ../cloud-ui
git pull origin master
cd ../
# not needed on newer git v's
git submodule update --init --recursive

# init submodules needed after clone
git clone git@github.com:jasenmichael/CloudKi-modules.git modules
cd modules
git submodule update --init --recursive

```