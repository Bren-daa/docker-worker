FROM node:12
WORKDIR /Users/brenda/GitHub/docker-worker/planner/
COPY package*.json main.js ./
RUN npm install
EXPOSE 8080
CMD [ "node", "main.js"]