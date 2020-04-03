FROM node:alpine
WORKDIR './app'
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
#for production we use "npm run start" instead of "npm run dev"
