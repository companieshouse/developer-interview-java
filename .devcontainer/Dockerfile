FROM amazoncorretto:21-al2023-jdk

# Ensure required tools for VS Code Server installation are available
# `tar -xz` requires gzip; install both tar and gzip.
RUN dnf install -y tar gzip git && dnf clean all
