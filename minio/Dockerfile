FROM minio/minio

LABEL maintainer="Quang Ho <hnquang112@yahoo.com.vn>"

EXPOSE ${MINIO_PORT}

ENV MINIO_ACCESS_KEY=${MINIO_ACCESS_KEY}
ENV MINIO_SECRET_KEY=${MINIO_SECRET_KEY}

ENTRYPOINT ["minio", "server", "${MINIO_BASE_PATH}"]
