FROM node

WORKDIR /app

RUN npm install  

COPY . .

EXPOSE 80  
# expose 80 to our local machine
 
CMD ["node", "server.js"]
# always at the end 