FROM node:16

RUN mkdir -p /app
WORKDIR /app
COPY . /app/
RUN yarn install && yarn build
ENV WEB_PORT=3001
EXPOSE 3001
CMD ["yarn","start"]
