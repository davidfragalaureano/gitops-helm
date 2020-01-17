# Dockerfile example for the hello-world chart
FROM busybox
COPY app/index.html /www/index.html
EXPOSE 8005
CMD httpd -p 8005 -h /www; tail -f /dev/null
