FROM node:alpine

WORKDIR /imposters
RUN npm install -g mountebank

COPY . .
EXPOSE 2525
ENTRYPOINT ["mb"]