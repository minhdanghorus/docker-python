FROM node:18-alpine
WORKDIR /core
ENV PATH  ./node_modules/.bin:$PATH
COPY package.json .
RUN npm install
COPY . .
EXPOSE 5173
CMD ["npm", "run", "dev"]
