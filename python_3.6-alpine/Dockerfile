FROM python:3.6-alpine
LABEL maintainer "UshioShugo<ushio.s@gmail.com>"

RUN apk update && \
	apk add --no-cache --virtual .pip \
	g++ && \
	pip install \
	grpcio \
	grpcio-tools \
	googleapis-common-protos && \
	apk del .pip

ENTRYPOINT [ "python" ]
