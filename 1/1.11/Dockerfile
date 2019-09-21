FROM node:10

COPY . .
WORKDIR /backend-example-docker-master
RUN node -v && npm -v
RUN npm install
CMD [ "npm", "start" ]

