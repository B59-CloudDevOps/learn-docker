FROM            docker.io/redhat/ubi9:latest  
RUN             dnf install -y nginx
RUN             rm -rf /usr/share/nginx/html/*
COPY            index.html /usr/share/nginx/html/index.html
ENTRYPOINT      ["nginx", "-g", "daemon off;"]
EXPOSE          80   