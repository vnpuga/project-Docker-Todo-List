FROM node:14-alpine AS todobackend
WORKDIR /back-end
EXPOSE 3001
ADD node_modules.tar.gz .
COPY . /back-end
CMD [ "npm", "start" ]
