FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/Lazack28/Lazack-md /root/Lazack-md
WORKDIR /root/Lazack-md/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
