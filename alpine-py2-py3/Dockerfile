FROM python:3-alpine

RUN apk update && apk upgrade && \
    apk add --no-cache python2 py2-pip bash && \
    pip2 install --upgrade pip setuptools && \
    rm -rf /root/.cache

CMD ["bash"]