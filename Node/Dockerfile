FROM node:13.3-alpine

ENV PORT 3000

#create app directory
#WORKDIR /usr/src/app
WORKDIR /home/api
RUN chown -R node:node /home/api

#Install dependencies app
COPY package*.json ./

RUN npm install

EXPOSE 3000
CMD ["npm","run","start"]