FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/Mayorpromise /MAYOR-MD /root/MAYOR-MD
WORKDIR /root/MAYOR-MD/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
