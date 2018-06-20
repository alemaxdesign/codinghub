FROM amd64/busybox

MAINTAINER admin@alemaxdesign.cloud

ADD codinghub/index.html /www/index.html
EXPOSE 80
CMD httpd -p 80 -h /www; tail -f /dev/null
