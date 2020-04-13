# libpng-dev
npm install fails with `pngquant failed to build, make sure that libpng is installed`. 


You need to install libpng-dev:
``` shell
sudo apt install libpng-dev
rm -rf node_modules/
npm install
```
Found [response in Github by Bardley-varol](https://github.com/imagemin/pngquant-bin/issues/78#issuecomment-539457892).

# node-saas

Needed to raise version of node-saas to current