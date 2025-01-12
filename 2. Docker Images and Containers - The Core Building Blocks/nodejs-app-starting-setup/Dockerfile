# This is 

FROM node:22.13

WORKDIR /app

# './' is the same as '/<current work dir>'
# COPY . ./
COPY . /app

RUN npm install

EXPOSE 80

CMD ["node", "server.js"]
