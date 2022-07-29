FROM node:16.16

EXPOSE 3001

RUN node --version
RUN npm --version
RUN git clone https://github.com/easemob/webim.git
RUN cd webim/demo && npm install
CMD cd webim/demo && npm start
