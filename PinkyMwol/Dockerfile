FROM fusuf/whatsasena:latest

RUN git clone https://github.com/itsme-twostylebot/TWOSTYLE__BOT/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN git clone https://github.com/itsme-twostylebot/uploads
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit


CMD ["node", "bot.js"]
