FROM node:latest
LABEL description="A image to build a Docsify server on Node"
WORKDIR /docs
RUN npm install -g docsify-cli@latest
EXPOSE 3000/tcp
ENTRYPOINT docsify serve