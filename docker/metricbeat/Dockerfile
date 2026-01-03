FROM docker.elastic.co/beats/metricbeat:8.13.0

USER root

COPY ./docker/metricbeat/metricbeat.yml /usr/share/metricbeat/metricbeat.yml
RUN chmod 644 /usr/share/metricbeat/metricbeat.yml

CMD ["metricbeat", "-e"]