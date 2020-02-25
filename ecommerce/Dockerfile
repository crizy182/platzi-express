FROM node:13

COPY [".","/usr/src/"]

WORKDIR /usr/src

RUN npm install

EXPOSE 8000

CMD ["node","index.js"]