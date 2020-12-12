FROM docker/whalesay:latest

RUN apt -y update && apt install -y fortunes
CMD /usr/games/fortune -a | cowsay

