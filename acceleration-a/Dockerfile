FROM node:10.14.2-alpine
MAINTAINER  Wasim Akram
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY . /usr/src/app
RUN yarn install && yarn build
EXPOSE 3002
CMD ["yarn", "start"]