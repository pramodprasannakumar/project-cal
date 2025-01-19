FROM node:16

RUN mkdir -p /app
WORKDIR /app
COPY . /app/
RUN yarn install && yarn build
ENV WEB_PORT=3000
EXPOSE 3000
CMD ["yarn","start"]
