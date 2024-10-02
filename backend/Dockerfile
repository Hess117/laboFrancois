FROM node:21-alpine3.17

WORKDIR /home/node/app

COPY *.js /home/node/app/
COPY package*.json /home/node/app/

RUN ["npm", "install"]
CMD ["node","index.js"]
