docker image build . --tag license-server

docker run -t -p 1017:1017 --restart=always -d --name 'xx-license-server' license-server:latest
