FROM nginx:1.17.3


#对外暴露端口
EXPOSE 80 8000

RUN rm /etc/nginx/conf.d/default.conf

RUN mkdir -p /opt/nginx/static
RUN mkdir -p /opt/nginx/html
RUN mkdir -p /opt/nginx/excel
RUN mkdir -p /opt/nginx/logs
RUN mkdir -p /usr/local/hexo/public
RUN mkdir -p /opt/yaojiaqi.com/cert
RUN mkdir -p /opt/blog.yaojiaqi.com/cert
