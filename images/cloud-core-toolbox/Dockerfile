# Cloud Core toolbox image
# Placeholder for Terraform, Ansible and Azure CLI tools.
FROM ubuntu:24.04

RUN apt-get update && apt-get install -y \
    curl \
    unzip \
    python3 \
    python3-pip \
  && rm -rf /var/lib/apt/lists/*

RUN pip3 install ansible azure-cli

CMD ["/bin/bash"]
