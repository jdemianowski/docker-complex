FROM node:alpine

WORKDIR '/app'

COPY ./package.json ./

RUN npm install
RUN npm config set ignore-scripts false

COPY ./ ./

CMD ["npm", "run", "start"]