# Specify a base image
FROM node:alpine

WORKDIR /app
COPY ./package.json ./

RUN npm install

# copy over everything else
COPY ./ ./

CMD ["npm", "run", "start"]