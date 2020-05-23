FROM node:alpine
WORKDIR '/app'
COPY package.json .
RUN npm install
COPY . .
#Here this is the only difference between DEV and PROD environment. 
# "dev" is for DEV environment and "start" is for prod
CMD ["npm", "run", "start"]