FROM cypress/included:4.1.0

WORKDIR /app
COPY ./cypress ./cypress
COPY ./cypress.json ./cypress.json
COPY ./package.json ./package.json
#COPY ./node_modules ./node_modules
COPY ./package-lock.json ./package-lock.json
#CMD npm install

#RUN npx cypress run
#sudo chmod 777 /var/run/docker.sock
#docker run -it -v $PWD:/e2e -w /e2e --entrypoint=cypress cypress/included:4.1.0 run
#docker run -t cypress:1 . 
