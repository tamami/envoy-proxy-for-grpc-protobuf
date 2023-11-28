https://intuting.medium.com/using-protocol-buffers-in-angular-96b4f8ab18d4

running:
docker run -d -v "$(pwd)"/envoy.yaml:/etc/envoy/envoy.yaml:ro -p 80:80 -p 9901:9901 envoyproxy/envoy:v1.14.1