FROM node:14-alpine
WORKDIR /todo-app-frontend
COPY . .
ADD node_modules.tar.gz .
EXPOSE 3000
CMD ["npm", "start"]
