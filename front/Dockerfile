FROM node:14.15.1-alpine

ENV APP_HOME /app
RUN mkdir -p $APP_HOME
WORKDIR $APP_HOME

# RUN apk update && npm install -g @vue/cli
RUN apk update
COPY package.json .
RUN yarn install