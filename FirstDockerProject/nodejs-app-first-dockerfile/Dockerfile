FROM node

WORKDIR /app  
# makes sure the all the commands are ran in this folder like, npm install

COPY . /app    
# copies content from rooot on my computer to /app on the docker container

RUN npm install

EXPOSE 80
# dosent actually expose the port but a best practive that tells the users that port 80 is what will be exposed

CMD ["node", "server.js"]
 #CMD HELP RUNS COMMAND AFTER THE container is running not whe it being prepared