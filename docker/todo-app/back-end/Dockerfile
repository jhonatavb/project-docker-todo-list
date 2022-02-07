FROM node:14-alpine
WORKDIR /app
COPY . .
EXPOSE 3001
RUN tar -xf /app/node_modules.tar.gz
CMD ["npm", "start"]
