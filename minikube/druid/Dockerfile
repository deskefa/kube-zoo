FROM imply/imply:2.5.8

EXPOSE 9095

#RUN   sed -i "s|some-original-string|the-new-string |g" /etc/sysctl.conf

WORKDIR /opt/imply
ENTRYPOINT cd /opt/imply && bin/supervise -c conf/supervise/quickstart.conf
