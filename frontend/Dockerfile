FROM node:latest as builder

WORKDIR /app

#use this
RUN git clone https://github.com/ISSSE31PTDMSSGroup4/PEPMProjectFrontend.git /app
#and not copy
#COPY ../PEPMProjectFrontend /app
RUN npm install
RUN npm run build
