FROM node:12-alpine3.9
COPY package.json /myapp/
RUN npm install --production
COPY src/ /myapp/src/
CMD ["node", "src/index.js"]