FROM node:latest as builder

WORKDIR /app


RUN git clone https://github.com/ISSSE31PTDMSSGroup4/PEPMProjectFrontend.git /app
RUN npm install
RUN npm run build
