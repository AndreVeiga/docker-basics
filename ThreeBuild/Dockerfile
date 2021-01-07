# Aula de Docker com copia de arquivos

FROM nginx:latest
LABEL maintainer="Elton Veiga <soutomachado1@gmail.com>"

RUN echo '<h1>Sem conteúdo</h1>' > /usr/share/nginx/html/conteudo.html
COPY *.html /usr/share/nginx/html/