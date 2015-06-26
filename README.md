mbentley/nginx-demo
===================

Build:
`docker build -t mbentley/nginx-demo .`

Push:
`docker push mbentley/nginx-demo`

Usage:
`docker run -it -p 80:80 mbentley/nginx-demo`

Interactive volume:
`docker run -it -p 80:80 -v $(pwd):/usr/share/nginx/html mbentley/nginx-demo`
