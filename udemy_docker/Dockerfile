FROM node:alpine
WORKDIR /usr/app
# make sure that npm install doesnt run at any change, but only package.json change
COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm","start"]