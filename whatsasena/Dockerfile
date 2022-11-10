FROM souravkl11/raganork:latest

RUN git clone https://github.com/OminduAnjane/Queen-Lora-5.0V.git /root/queenlora
WORKDIR /root/queenlora/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
