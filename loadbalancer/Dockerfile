FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
COPY loadbalancer.conf /etc/nginx/conf.d/default.conf
EXPOSE 80