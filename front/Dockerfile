FROM node:16.13.2
WORKDIR /sample-app
COPY ./sample-app /sample-app

RUN npm install
RUN npm install axios

CMD ["npm", "run", "dev"]