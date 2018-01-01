FROM nginx

COPY _ssl /etc/nginx/ssl
COPY _conf/etc/nginx/conf.d /etc/nginx/conf.d
COPY _conf/etc/nginx/nginx.conf /etc/nginx/nginx.conf
COPY _conf/etc/nginx/modules/echo-nginx-module-0.61 /etc/nginx/modules/echo-nginx-module-0.61



COPY _site /usr/share/nginx/html

#VOLUME /usr/share/nginx/html
#VOLUME /etc/nginx

RUN apt-get update

# RUN apt-get install -y apt-utils
# RUN apt-get install -y vim

RUN apt-get install -y wget
RUN apt-get install -y build-essential

# RUN apt-get install -y gnupg
# RUN apt-get install -y gnupg1
# RUN apt-get install -y gnupg2
# RUN wget -qO - https://openresty.org/package/pubkey.gpg | apt-key add -
# RUN apt-get -y install software-properties-common
# RUN add-apt-repository -y "deb http://openresty.org/package/debian $(lsb_release -sc) openresty"
# RUN apt-get update
# RUN apt-get install -y openresty
# RUN service openresty start

RUN wget 'http://nginx.org/download/nginx-1.11.2.tar.gz'
RUN tar -xzvf nginx-1.11.2.tar.gz
RUN export PATH="/usr/bin:$PATH"
RUN cd nginx-1.11.2/; ./configure --without-http_rewrite_module --without-http_gzip_module --add-module=/etc/nginx/modules/echo-nginx-module-0.61;

# RUN .configure --prefix=/opt/nginx --add-module=/etc/nginx/modules/echo-nginx-module-0.61
# RUN sleep 1
# RUN .configure --prefix=/opt/nginx --add-module=/etc/nginx/modules/echo-nginx-module-0.61

RUN cd nginx-1.11.2/; make
RUN cd nginx-1.11.2/; make install
