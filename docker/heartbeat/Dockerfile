FROM docker.elastic.co/beats/heartbeat:8.11.0

USER root

COPY ./docker/heartbeat/heartbeat.yml /usr/share/heartbeat/heartbeat.yml
RUN chmod 644 /usr/share/heartbeat/heartbeat.yml

CMD ["heartbeat", "-e"]