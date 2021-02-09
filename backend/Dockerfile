FROM node:13-alpine
LABEL maintainer="eslam.adel.muhammad@gmail.com"

WORKDIR /app
ADD . /app
RUN npm i
RUN cp .env.sample .env
RUN sed -i 's/localhost/database/' .env
RUN npm run build
RUN ls