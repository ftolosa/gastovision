# Dockerfile.frontend
FROM node:14

WORKDIR /app

COPY frontend/package.json .
COPY frontend/package-lock.json .
RUN npm install

COPY frontend .

CMD ["npm", "start"]
