FROM nginx

COPY _ssl /etc/nginx/ssl
COPY _conf/etc/nginx/conf.d /etc/nginx/conf.d
COPY _conf/etc/nginx/nginx.conf /etc/nginx/nginx.conf
COPY _conf/etc/nginx/modules /etc/nginx/modules
COPY _site /usr/share/nginx/html

#VOLUME /usr/share/nginx/html
#VOLUME /etc/nginx


# RUN apt-get update
# # RUN apt-get install -y vim
# RUN apt-get install -y build-essential
# # -y During installing, when instoller ask you like "Y/N?", -y configuration will answer "Y" automatically.
# # --no-install-recommends install only main dependencies (not recommended dependencies)
# RUN apt-get install -y --no-install-recommends apt-utils
# RUN apt-get install -y libpcre3 libpcre3-dev
# RUN apt-get install -y zlib1g-dev 

# RUN apt-get install -y wget
# RUN wget 'http://nginx.org/download/nginx-1.13.8.tar.gz'
# RUN tar -xzvf nginx-1.13.8.tar.gz
# RUN export PATH="/usr/bin:$PATH"
# RUN cd nginx-1.13.8/; ./configure --with-compat --add-dynamic-module=/etc/nginx/modules/echo-nginx-module-0.61/
# RUN cd nginx-1.13.8/; make modules; cp /nginx-1.13.8/objs/ngx_http_echo_module.so /etc/nginx/modules/;

# RUN cd nginx-1.13.8/; ./configure --with-compat --add-dynamic-module=/etc/nginx/modules/nginx-delay-module-master;
# RUN cd nginx-1.13.8/; make modules; cp /nginx-1.13.8/objs/ngx_http_delay_module.so /etc/nginx/modules/;

# RUN cp /nginx-1.13.8/objs/ngx_http_echo_module.so /usr/share/nginx/html/
# RUN cp /nginx-1.13.8/objs/ngx_http_delay_module.so /usr/share/nginx/html/



# RUN apt-get update
# RUN apt-get install -y build-essential
# # -y During installing, when instoller ask you like "Y/N?", -y configuration will answer "Y" automatically.
# # --no-install-recommends install only main dependencies (not recommended dependencies)
# RUN apt-get install -y --no-install-recommends apt-utils
# RUN apt-get install -y libpcre3 libpcre3-dev
# RUN apt-get install -y zlib1g-dev 
# RUN apt-get install -y wget
# RUN wget 'http://nginx.org/download/nginx-1.13.8.tar.gz'
# RUN tar -xzvf nginx-1.13.8.tar.gz
# RUN cd nginx-1.13.8/; ./configure --add-module=/etc/nginx/modules/echo-nginx-module-0.61/ 
# # RUN cd nginx-1.13.8/; ./configure --add-module=/etc/nginx/modules/nginx-delay-module-master/
# RUN cd nginx-1.13.8/; make -j2
# RUN cd nginx-1.13.8/; make install

# RUN cp /nginx-1.13.8/objs/ngx_http_echo_module.so /etc/nginx/modules/
# RUN cp /nginx-1.13.8/objs/ngx_http_echo_module.so /usr/share/nginx/html/