FROM node:latest

EXPOSE 8080
WORKDIR /bindmount
COPY package-lock.json package.json ./

RUN npm install --no-progress --ignore-optional

# webpack-dev-server --host 0.0.0.0 --hot --inline
CMD npm run start:dev