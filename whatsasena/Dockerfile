FROM fusuf/whatsasena:latest

RUN git clone https://github.com/SLdevilX/102 /root/102
WORKDIR /root/102/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
