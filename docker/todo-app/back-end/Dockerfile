
FROM node:14-alpine
WORKDIR /back-end
COPY . .
ADD ./node_modules.tar.gz .
EXPOSE 3001
ENTRYPOINT ["npm", "start"]