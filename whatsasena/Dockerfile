FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Muhammednoufal077/Mr-Oopz /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
