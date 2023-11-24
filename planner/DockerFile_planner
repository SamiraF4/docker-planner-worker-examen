FROM node:14
WORKDIR /app
COPY package*.json ./
ENV TASKS=4 \ 
PORT=3000
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "main.js"]