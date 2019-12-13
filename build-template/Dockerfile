FROM amazoncorretto:11.0.5

## Make application directory
RUN set -x && mkdir -p /opt/app

## Copy application
COPY ./build/libs/sample-0.0.1-SNAPSHOT.jar /opt/app

## Environment Variables
STOPSIGNAL 15
EXPOSE 8080
CMD ["java","-jar","/opt/apps/sample-0.0.1-SNAPSHOT.jar"]
