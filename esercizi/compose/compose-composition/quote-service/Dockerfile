FROM node:alpine
WORKDIR /app
COPY package.json .
RUN npm set progress=false && \
    npm config set depth 0 && \
    npm install --only=production && \
    npm cache clean --force
COPY src src
ENTRYPOINT ["npm", "run", "start"]
EXPOSE 3000
