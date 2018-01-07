# FROM nginx

# COPY _ssl /etc/nginx/ssl
# COPY _conf/etc/nginx/conf.d /etc/nginx/conf.d
# COPY _conf/etc/nginx/nginx.conf /etc/nginx/nginx.conf
# COPY _conf/etc/nginx/modules /etc/nginx/modules
# COPY _site /usr/share/nginx/html


# FROM quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.9.0
# FROM ehekatl/docker-nginx-http2
FROM openresty/openresty
# RUN mkdir /etc/nginx/modules
COPY _ssl /etc/nginx/ssl
# COPY _conf/etc/nginx/conf.d /etc/nginx/conf.d
# COPY _conf/etc/nginx/nginx_for_ehekatl:docker-nginx-http2.conf /etc/nginx/nginx.conf
COPY _conf/etc/nginx/nginx_for_ehekatl:docker-nginx-http2.conf /usr/local/openresty/nginx/conf/nginx.conf

# COPY _conf/etc/nginx/modules /etc/nginx/modules
COPY _site /usr/share/nginx/html



# FROM quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.9.0
# COPY _ssl /etc/nginx/ssl
# COPY _conf/etc/nginx/nginx.ingress.controller.conf /etc/nginx/nginx.conf
# # COPY _conf/etc/nginx/modules /etc/nginx/modules
# COPY _site /usr/share/nginx/html

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

# RUN apt-get install -y libdata-compare-perl
# RUN apt-get install -y wget
# RUN wget https://www.openssl.org/source/openssl-1.0.2n.tar.gz
# RUN tar -xzvf openssl-1.0.2n.tar.gz
# RUN cd openssl-1.0.2n; ./config shared
# RUN cd openssl-1.0.2n; ./config shared ./config --prefix=/usr --openssldir=/usr/local/openssl shared
# RUN cd openssl-1.0.2n; make
# RUN cd openssl-1.0.2n; make install

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





###############################################################
# SUCCSS !!
#
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
# RUN export PATH="/usr/bin:$PATH"
# RUN cd nginx-1.13.8/; ./configure --with-compat --add-dynamic-module=/etc/nginx/modules/nginx-delay-module-master
# RUN cd nginx-1.13.8/; make modules
# RUN cp /nginx-1.13.8/objs/ngx_http_delay_module.so /etc/nginx/modules
# RUN cp /nginx-1.13.8/objs/ngx_http_delay_module.so /usr/share/nginx/html
###############################################################


###############################################################
# SUCCSS !!
#
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
# RUN export PATH="/usr/bin:$PATH"
# RUN cd nginx-1.13.8/; ./configure --with-compat --add-dynamic-module=/etc/nginx/modules/nginx-delay-module-master
# RUN cd nginx-1.13.8/; make modules
# RUN cp /nginx-1.13.8/objs/ngx_http_delay_module.so /etc/nginx/modules
# RUN cp /nginx-1.13.8/objs/ngx_http_delay_module.so /usr/share/nginx/html
###############################################################




# RUN apt-get update
# RUN apt-get install -y build-essential
# # -y During installing, when instoller ask you like "Y/N?", -y configuration will answer "Y" automatically.
# # --no-install-recommends install only main dependencies (not recommended dependencies)
# RUN apt-get install -y --no-install-recommends apt-utils

# RUN apt-get install -y zlib1g-dev
# RUN cd /etc/nginx/modules/LuaJIT-2.1.0-beta3-master; make;
# # RUN cd /etc/nginx/modules/LuaJIT-2.1.0-beta3-master; make install PREFIX=/etc/nginx/modules/luajit-module;
# RUN cd /etc/nginx/modules/LuaJIT-2.1.0-beta3-master; make install PREFIX=/usr/aaa;

# RUN apt-get install -y wget
# RUN wget 'http://nginx.org/download/nginx-1.13.8.tar.gz'
# RUN tar -xzvf nginx-1.13.8.tar.gz


#  # tell nginx's build system where to find LuaJIT 2.1:
# # RUN export LUAJIT_LIB=/usr/aaa/lib
# # RUN export LUAJIT_INC=/usr/aaa/include/luajit-2.1
# RUN sudo export PATH=$PATH;/usr/aaa/lib;/usr/aaa/include/luajit-2.1;

# # RUN cp -R /usr/aaa/lib/**/* /usr/local/lib
# # RUN cp -R /usr/aaa/include/**/* /usr/local
# RUN cd /nginx-1.13.8; ./configure \
#          # --with-ld-opt="-Wl,-rpath,/usr/aaa/lib" \
#          --with-ld-opt=-Wl,-rpath,/usr/aaa/lib \
#          --add-module=/etc/nginx/modules/ngx_devel_kit-0.3.0 \
#          --add-module=/etc/nginx/modules/lua-nginx-module-0.10.12rc1

# RUN cd nginx-1.13.8/; make -j2
# RUN cd nginx-1.13.8/; make install




# RUN apt-get update
# RUN apt-get install -y wget
# # build-essential needed to avoid the following error :
# # E: gnupg, gnupg2 and gnupg1 do not seem to be installed, but one of them is required for this operation
# RUN apt-get install -y build-essential
# # http://openresty.org/en/linux-packages.html
# # Debian

# # # import our GPG key:
# RUN wget -qO - https://openresty.org/package/pubkey.gpg | apt-key add -

# #     # for installing the add-apt-repository command
# #     # (you can remove this package and its dependencies later):
# RUN apt-get -y install software-properties-common

# #     # add the our official APT repository:
# RUN add-apt-repository -y "deb http://openresty.org/package/debian $(lsb_release -sc) openresty"

# #     # to update the APT index:
# RUN apt-get update
# # Then you can install a package, say, openresty, like this:

# #     sudo apt-get install openresty
# # This package also recommends the openresty-opm and openresty-restydoc packages so the latter two will also automatically get installed by default. If that is not what you want, you can disable the automatic installation of recommended packages like this:

# RUN apt-get -y install --no-install-recommends openresty

# RUN cd usr/local/openresty; ./configure --with-luajit && make && make install
