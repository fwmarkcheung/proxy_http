To build an apache proxy server with the directive:


docker build -t proxy_http:2.4 .

Tag and push it to quay:

docker tag proxy_http:2.4 quay.io/mcheung/proxy_http:2.4

docker push quay.io/mcheung/proxy_http:2.4
