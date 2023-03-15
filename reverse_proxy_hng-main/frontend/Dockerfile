# FROM node:13.12.0-alpine

# RUN mkdir -p /app/frontend
# WORKDIR /app/frontend

# COPY package.json /app/frontend
# RUN npm install 
# COPY . /app/frontend
# RUN npm run build
# EXPOSE 3000
# CMD ["serve", "-s", "build"]

FROM node:13.12.0-alpine
WORKDIR /app/frontend

COPY package.json ./
RUN npm install 
COPY . ./
EXPOSE 3000
CMD ["npm", "start"]
