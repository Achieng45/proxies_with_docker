# Use a lightweight web server image as the base
FROM stephanieachieng/hello:latest


COPY nginx.conf /etc/nginx/conf.d/default.conf

#copy cert and key in ssh
COPY ssh /nginx/keys


EXPOSE 80
EXPOSE 443
