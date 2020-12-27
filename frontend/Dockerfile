# The first stage
# Build React static files
FROM node:15.5-alpine

WORKDIR /app/frontend/app
COPY ./frontend/app/package.json /app/frontend/app
RUN npm install

COPY ./frontend/app /app/frontend/app

CMD ["npm", "run", "start"]
