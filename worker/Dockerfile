FROM node:12
WORKDIR /Users/brenda/GitHub/docker-worker/worker/
COPY package*.json main.js ./
RUN npm install
EXPOSE 3000 3001 3003 3004
CMD [ "node", "main.js"]