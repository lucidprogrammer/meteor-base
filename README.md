[![](https://badge.imagelayers.io/lucidprogrammer/meteor-production-base:latest.svg)](https://imagelayers.io/?images=lucidprogrammer/meteor-production-base:latest 'Get your own badge on imagelayers.io')

# How to Build


```
docker build --build-arg METEOR_VERSION=1.8.1  -t yourusername/meteor .

```

# What is available in the container when deployed?

- [x] Node and Npm which is packaged already with meteor, so exact versions of node and npm
- [x] Mongo Client and server already in path as it is already available with meteor.
- [x] All the meteor installed npm packages available in NODE_PATH
