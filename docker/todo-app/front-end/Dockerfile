FROM node:14-alpine
WORKDIR /app
EXPOSE 3000
COPY . .
RUN tar -xf /app/node_modules.tar.gz
CMD ["npm", "start"]
