FROM node:10.16.0-stretch-slim

### use folder /frontend
RUN mkdir -p /frontend
WORKDIR /frontend

### install via npm
RUN npm install --no-optional -g @vue/cli
RUN npm install --no-optional -g @vue/cli-service-global

### or install vue-cli via yarn
# RUN yarn global add @vue/cli
# RUN yarn global add @vue/cli-service-global

# wait for cli commands
CMD /bin/sleep 365d
