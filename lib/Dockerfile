FROM quay.io/xelectra/xasena:latest
RUN git clone https://github.com/dayanisuru/KING-ISUWA /root/X-Asena
WORKDIR /root/X-Asena
RUN yarn install --network-concurrency 1
CMD ["node", "bot.js"] 


