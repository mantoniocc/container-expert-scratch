FROM alpine

# RUN, COPY, ADD, FROM

WORKDIR /app
# ADD vs COPY
COPY myapp.sh /app/

RUN ls /app && chmod +x /app/myapp.sh && apk add --update bash

#CMD [ "./myapp.sh" ]
ENTRYPOINT [ "./myapp.sh" ]