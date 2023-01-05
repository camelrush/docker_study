FROM ubuntu:20.04
RUN apt-get update -y && \
    apt-get install -y nginx
ENV TESTENV="Takada"

# よく使うのが、locat,production
# ENV APP_ENV="production"     # or development, staging

CMD ["nginx", "-g", "daemon off;"]
