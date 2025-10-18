FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
ENV MONGO="true" \
    REDIS_URL="redis://redis:6379" \
    MONGO_URL="mngodb://mongodb:27017/users"
RUN npm install