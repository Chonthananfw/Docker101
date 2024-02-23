FROM node:alpine
RUN npm install -g newman newman-reporter-htmlextra
WORKDIR /newman

COPY . .
ENTRYPOINT ["newman"]