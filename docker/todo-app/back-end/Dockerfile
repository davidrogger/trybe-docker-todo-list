FROM node:14-alpine
WORKDIR /app
COPY . .
ADD node_modules.tar.gz .
# RUN npm install
EXPOSE 3001
CMD ["npm", "start"]