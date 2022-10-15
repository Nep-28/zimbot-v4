FROM fusuf/whatsasena:latest

RUN git clone https://github.com/nep-28/zimbot-v4 /nep-28/Zimbotv4

WORKDIR /nep-28/Zimbotv4

ENV TZ=Africa/Harare

RUN npm install

RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
