FROM eclipse-temurin:17.0.7_7-jdk

ADD src/main/docker/kafdrop.sh /
ADD kafdrop*tar.gz /

RUN chmod +x /kafdrop.sh

EXPOSE 9000

ENTRYPOINT ["/kafdrop.sh"]
