FROM node:13-alpine
LABEL maintainer="eslam.adel.muhammad@gmail.com"

RUN mkdir app
WORKDIR /app
ADD . /app
RUN npm i
RUN npm run build
RUN ls