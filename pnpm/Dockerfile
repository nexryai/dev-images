FROM node:22

RUN npm install -g pnpm
RUN apt-get update && apt-get upgrade -y && \
    apt-get install -y git golang && \
    apt-get clean autoclean && \
    apt-get autoremove -y && \
    rm -rf /var/lib/{apt,dpkg,cache,log}/
