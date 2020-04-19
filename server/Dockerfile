FROM node:alpine
WORKDIR /home/complex
COPY ./package.json ./           
RUN npm install
COPY . .
CMD ["npm", "run", "start"]

