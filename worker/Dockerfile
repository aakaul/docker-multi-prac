FROM node:alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm i 
COPY . .
CMD ["npm","run","start"];


#43b843a5e95a