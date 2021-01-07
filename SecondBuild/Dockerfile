# Aula de build com argumentos
#
# docker image build --build-arg S3Bucket=myapp -t second-build .

FROM debian
LABEL maintainer="Aluno Elton <aluno at soutomachado1@gmail.com>"

ARG S3Bucket=files
ENV S3Bucket=${S3Bucket}
