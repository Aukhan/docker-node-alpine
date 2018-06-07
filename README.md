# node-alpine
An node alpine image to include build dependencies required by node-gyp.

It does increase the size of the image by approximately 150MB but the whole idea is to 
save time re-installing all those deps on every service update or container rebuild

# usage
`docker pull aukhan/node-alpine`

# usage in Dockerfile
``` 
    FROM aukhan/node-alpine 
 
    RUN npm install 
 
 ```
