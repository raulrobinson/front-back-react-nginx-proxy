FROM node:12.18.2
WORKDIR /app
COPY ./package.json /app/package.json
COPY ./package-lock.json /app/package-lock.json
RUN npm ci
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
