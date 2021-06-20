FROM fusuf/whatsasena:latest

RUN git clone https://github.com/shahizz/WhatsAsenaDuplicated.git /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV REPO="https://shahizz/WhatsAsenaDuplicated"
ENV TZ=Europe/Istanbul

RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["run.sh"]
shahizz
/
WhatsAsenaDuplicated
