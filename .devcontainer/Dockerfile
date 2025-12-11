FROM mcr.microsoft.com/devcontainers/javascript-node:1-20-bullseye

RUN apt-get update && apt-get install -y python3 python3-pip

RUN npm install -g @vue/cli && \
    pip3 install flask