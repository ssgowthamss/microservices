FROM node:8
RUN echo " Try to build my application"
COPY . /var/www
WORKDIR /var/www
RUN npm clean install
EXPOSE 3000    #npm portno
# EXPOSE 31448
ENTRYPOINT ["npm","start"]
