FROM debian:stretch

# Install dependencies
RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        libc6 \
        libgcc1 \
        ca-certificates \
        curl \
        unzip

# Install the Azure CLI
RUN curl -sL https://aka.ms/InstallAzureCLIDeb | bash

# Install Packer
RUN curl https://releases.hashicorp.com/packer/1.4.3/packer_1.4.3_linux_amd64.zip > /tmp/packer.zip \
    && unzip /tmp/packer.zip -d /usr/local