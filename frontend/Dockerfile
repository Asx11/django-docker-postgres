FROM node:17.3.1-alpine
WORKDIR /app/frontend

COPY package.json package-lock.json ./
RUN npm install 
RUN npm install react-scripts@3.4.1 -g 
COPY . ./
EXPOSE 3000
CMD ["npm","start"]
