FROM node:12.18.1-alpine

WORKDIR /app
COPY . .
RUN npm install
RUN apt-get update
RUN apt-get install vim -ys
EXPOSE 3333

CMD ["npm", "start", "propo"]