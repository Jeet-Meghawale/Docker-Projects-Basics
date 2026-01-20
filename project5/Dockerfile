FROM node:14-alpine

WORKDIR /app

COPY . /app/
RUN npm i
EXPOSE 3000

ENV Name=project5

CMD [ "npm","start" ]