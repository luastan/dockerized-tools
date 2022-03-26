FROM python:3.10-alpine

RUN apk add --update git

RUN git clone --depth 1 https://github.com/sqlmapproject/sqlmap.git sqlmap

WORKDIR /sqlmap

ENTRYPOINT ["python", "sqlmap.py"]
