FROM openjdk:8u232-stretch

RUN useradd -ms /bin/bash libertya

ADD ServidorOXP/ /ServidorOXP
RUN chown -R libertya:libertya /ServidorOXP
RUN mkdir /var/run/libertya
RUN chown libertya:libertya /var/run/libertya

USER libertya

ENV OXP_HOME=/ServidorOXP

WORKDIR /ServidorOXP
CMD sleep infinity
RUN ./ConfigurarAuto.sh
CMD ./utils/IniciarServidor.sh

EXPOSE 1099
EXPOSE 8080
EXPOSE 8443