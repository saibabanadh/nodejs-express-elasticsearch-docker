FROM node:4.3.2

RUN useradd --user-group --create-home --shell /bin/false app

RUN npm install nodemon -g

ENV HOME=/home/app

USER root
RUN chown -R app:app $HOME
USER app
