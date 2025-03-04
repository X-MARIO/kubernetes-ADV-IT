# kubernetes-ADV-IT

1. `docker build -t xmario/myk8sapp .`
2. `docker login`
3. `docker push xmario/myk8sapp:latest`
4. `docker run -it -p 1234:80 xmario/myk8sapp:latest`