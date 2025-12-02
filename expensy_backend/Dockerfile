FROM ubuntu:resolute-20251101

RUN apt update && apt install -y nodejs npm

WORKDIR /expensy_backend

COPY . .

RUN npm install 

CMD ["npm", "start"]
