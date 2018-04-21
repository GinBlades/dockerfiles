# Build with
#    docker build -f .\ruby-node\Dockerfile -t local:ruby-node .
FROM ruby:2.5.1
RUN apt-get update -qq && apt-get install -y build-essential
RUN curl -sL https://deb.nodesource.com/setup_8.x | bash -
RUN apt-get install -y nodejs
