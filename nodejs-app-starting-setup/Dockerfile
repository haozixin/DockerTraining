FROM node

WORKDIR /app

COPY . .

RUN npm install  

EXPOSE 80  
# expose 80 to our local machine
 
CMD ["node", "server.js"]
# always at the end 