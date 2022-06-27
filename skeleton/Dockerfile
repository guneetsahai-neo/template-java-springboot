FROM amazoncorretto:18-alpine3.15
ENTRYPOINT ["/usr/bin/myDummyApp.sh"]

COPY myDummyApp.sh /usr/bin/myDummyApp.sh
RUN chmod +x /usr/bin/myDummyApp.sh
COPY target/myDummyApp.jar /usr/share/myDummyApp/myDummyApp.jar