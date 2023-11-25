FROM node:14
WORKDIR /Users/samirafawaz/Documents/docker-planner-worker-examen/worker
COPY package*.json main.js ./
RUN npm install
EXPOSE 3000 3001
CMD [ "node", "main.js"]