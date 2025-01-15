FROM nginx:1.21.6

ARG CACHEBUST=1

RUN apt-get update && apt-get -y upgrade

RUN echo '<html><body><h1>This is my PERSONALIZED home page, Second version</h1></body></html>' > /usr/share/nginx/html/index.html