FROM nginxinc/nginx-unprivileged
COPY helloWorld.html /app/
COPY default.conf /etc/nginx/conf.d/default.conf
EXPOSE 8000
USER 1001
