FROM linuxserver/sickbeard:latest
LABEL org.freenas.interactive="false" \
      org.freenas.version="2" \
      org.freenas.upgradeable="true" \
      org.freenas.expose-ports-at-host="true" \
      org.freenas.autostart="true" \
      org.freenas.web-ui-protocol="http" \
      org.freenas.web-ui-port="8081" \
      org.freenas.web-ui-path="" \
      org.freenas.port-mappings="8081:8081/tcp" \
      org.freenas.volumes="[						\
          {								\
              \"name\": \"/config\",					\
              \"descr\": \"Database and Sickbeard configs\"		\
          },								\
          {								\
              \"name\": \"/data\",					\
              \"descr\": \"Sickbeard data volume\"			\
          }								\
      ]" \
      org.freenas.settings="[             \
          {               \
              \"env\": \"TZ\",            \
              \"descr\": \"Timezone - eg Europe/London\",   \
              \"optional\": true          \
          },                \
          {               \
              \"env\": \"PUID\",          \
              \"descr\": \"User ID - eg 1000\",                         \
              \"optional\": true          \
          },                \
          {               \
              \"env\": \"PGID\",          \
              \"descr\": \"Group ID - eg 1000\",                \
              \"optional\": true          \
          }               \
      ]"

