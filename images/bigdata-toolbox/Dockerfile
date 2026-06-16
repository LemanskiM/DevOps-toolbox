# BigData toolbox image
# Placeholder image for Kafka, Spark and Hadoop tooling.
FROM ubuntu:24.04

RUN apt-get update && apt-get install -y \
    curl \
    wget \
    unzip \
    default-jre \
    default-jdk \
  && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
