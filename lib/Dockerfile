FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/arthur1/ELSA_BOT-V2 /root/arthur1
WORKDIR /root/arthur1/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
