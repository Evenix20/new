FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Evenix20/new/root/new
WORKDIR /root/new/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
