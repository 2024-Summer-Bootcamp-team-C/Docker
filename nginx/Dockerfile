FROM nginx:latest

COPY nginx.conf /etc/nginx/nginx.conf
COPY certs /etc/nginx/certs

RUN apt-get update && apt-get install -y openssl

CMD ["nginx", "-g", "daemon off;"]
