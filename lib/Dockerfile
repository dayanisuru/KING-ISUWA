FROM quay.io/dayanisuru/king-isuwa:latest
RUN git clone https://github.com/dayanisuru/KING-ISUWA /root/ISUWA
WORKDIR /root/ISUWA
RUN yarn install --network-concurrency 1
CMD ["node", "bot.js"] 


