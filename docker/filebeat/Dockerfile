FROM docker.elastic.co/beats/filebeat:8.12.2

USER root

COPY ./docker/filebeat/filebeat.yml /usr/share/filebeat/filebeat.yml
RUN chmod 644 /usr/share/filebeat/filebeat.yml

CMD ["filebeat", "-e"]