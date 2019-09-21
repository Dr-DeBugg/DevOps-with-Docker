FROM node:10

COPY . .
WORKDIR /backend-example-docker-master
RUN node -v && npm -v
RUN npm install
ENV FRONT_URL=http://localhost:5000
CMD [ "npm", "start" ]

