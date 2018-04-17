# sandbox_docker
===

Overview
## tutorial docker httpd

step.1 build
docker build -t yusukeono/httpd:ver1.1 ~/build_httpd

step.2 run
docker run -itd -p 8000:80 --name web01 yusukeono/httpd:ver1.1
