FROM amazonlinux

RUN yum -y update && yum -y install nginx 
## && yum -y install php

COPY ./html/index.html /usr/share/nginx/html/index.html
#COPY ./html/index.php /usr/share/nginx/html/index.php

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80

