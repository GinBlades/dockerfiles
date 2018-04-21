# Build with
#    docker build -f .\rails-setup\Dockerfile -t local:rails-setup .
FROM local:ruby-node
RUN gem install bundler && gem install rails && npm install -g yarn
RUN mkdir /myapp
WORKDIR /myapp
EXPOSE 3000/tcp
VOLUME ["/myapp"]
ENTRYPOINT ["/bin/bash"]
