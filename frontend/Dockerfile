FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# Important environment variables for Docker
ENV HOST=0.0.0.0
ENV PORT=3000
ENV CI=true

EXPOSE 3000

CMD ["npm", "start"]