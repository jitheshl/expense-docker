FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
RUN npm install
ENV DB_HOST="expense"
CMD ["node","index.js"]
