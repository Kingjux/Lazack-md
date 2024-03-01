FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/mtaju/Lazack-md /root/mtaju
WORKDIR /root/mtaju/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
