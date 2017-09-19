FROM node:latest
ENV INSTALL_PATH=/<SERVICE_NAME>
RUN mkdir $INSTALL_PATH
WORKDIR $INSTALL_PATH
COPY package.json yarn.lock ./
RUN yarn install
ADD . .
