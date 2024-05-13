FROM node as react-hot-cold

ARG TOKEN

RUN apt-get update
RUN apt-get upgrade -y 
RUN apt-get install -y git

RUN git clone https://github.com/anamika8/react-hot-cold.git
WORKDIR /react-hot-cold


RUN npm i
RUN npm run build

CMD ls build