FROM node:20-alpine

RUN mkdir -p /home/app

COPY ./app /home/app

# set default dir so the commands executes in /home/app dir by default

WORKDIR /home/app

# execute npm install in /home/app

RUN npm install

# Now no need to specify the dir path because of WORKDIR

CMD ["node", "server.js"]
