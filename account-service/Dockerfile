FROM openjdk
MAINTAINER Wang Qing <wangq@jfrog.com>
ADD target/account-service.jar account-service.jar
RUN curl -SL http://example.com/postgres-$PG_VERSION.tar.xz
ENTRYPOINT ["java", "-jar", "/account-service.jar"]
EXPOSE 2222