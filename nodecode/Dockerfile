FROM amitpareek/ubuntunode:v1  

# Create app directory
#RUN mkdir /src/app


# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY . /src
#COPY /home/amit/nodecode/code/package.json /src

WORKDIR /src

RUN npm install
# If you are building your code for production
# RUN npm install --only=production


EXPOSE 8080
CMD [ "node", "/ssrc/app.js" ]

