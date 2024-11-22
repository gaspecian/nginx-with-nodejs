FROM node:22

WORKDIR /app
COPY . .
RUN npm ci

ENTRYPOINT [ "npm", "start" ]