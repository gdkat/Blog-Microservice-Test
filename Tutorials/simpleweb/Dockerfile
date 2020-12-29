FROM node:alpine

WORKDIR /usr/app

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD [ "npm", "start" ]

# docker build -t gdkat/simpleweb
# docker run -p 8080:8080 gdkat/simpleweb