FROM fusuf/whatsasena:latest

RUN git clone https://github.com/FASIL-NX/ZARA-NX /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/farhan-dqz/media

CMD ["node", "bot.js"]
