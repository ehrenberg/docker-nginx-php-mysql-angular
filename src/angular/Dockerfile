FROM node:current-alpine
WORKDIR /application

ENV PATH /application/node_modules/.bin:$PATH

COPY package.json /application/package.json

RUN npm install -g @angular/cli@13.3.7
RUN npm install --save-dev @angular-devkit/build-angular
RUN npm install

COPY . /application

EXPOSE 4200
