FROM cypress/base

WORKDIR /workspace
COPY . .
RUN rm -rf node_modules
RUN npm install
CMD [ "npm", "run", "test:e2e" ] 
