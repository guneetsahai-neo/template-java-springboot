FROM amazoncorretto:18-alpine3.15
ENTRYPOINT ["/usr/bin/${{values.artifact_id}}.sh"]

LABEL org.opencontainers.image.source=https://github.com/guneetsahai-neo/${{values.artifact_id}}

COPY ${{values.artifact_id}}.sh /usr/bin/${{values.artifact_id}}.sh
RUN chmod +x /usr/bin/${{values.artifact_id}}.sh
COPY target/${{values.artifact_id}}.jar /usr/share/${{values.artifact_id}}/${{values.artifact_id}}.jar