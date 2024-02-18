FROM node

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

# copy this directory to the container
COPY . .

EXPOSE 4000

CMD [ "npm","start" ]