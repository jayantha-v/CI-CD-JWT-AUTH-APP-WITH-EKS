FROM node:alpine

WORKDIR /app
COPY package.json .
RUN npm install --omit=dev
COPY . .
EXPOSE 86 
 
CMD ["npm", "start"]

