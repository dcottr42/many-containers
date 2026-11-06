FROM nginx
# Container Apps ingress answers on 80 and forwards to each app's target port
ENV CLIENT_PORT=80 API_PORT=80
COPY ./default.conf.template /etc/nginx/templates/default.conf.template
