FROM jboss/keycloak:7.0.0

ENV KEYCLOAK_USER=admin
ENV KEYCLOAK_PASSWORD=admin
ENV DB_ADDR=pg-keycloak
ENV DB_PORT=5432
ENV DB_USER=keycloak
ENV DB_PASSWORD=keycloak
ENV DB_DATABASE=keycloak
ENV DB_VENDOR=postgres
ENV PROXY_ADDRESS_FORWARDING=true

RUN mkdir /opt/jboss/keycloak/themes/mj-theme
COPY ./mj-theme/ /opt/jboss/keycloak/themes/mj-theme/
