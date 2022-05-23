FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/KALIPPAN-SER02/APARNA_MWOL_V3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
