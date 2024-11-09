FROM node:20

RUN apt update && apt install -y openjdk-17-jre graphviz && rm -rf /var/lib/apt/lists/*
RUN wget -O /usr/local/bin/plantuml.jar https://github.com/plantuml/plantuml/releases/download/v1.2024.7/plantuml-1.2024.7.jar

RUN npm i -g wollok-ts-cli

EXPOSE 3456
