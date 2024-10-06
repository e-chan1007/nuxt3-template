FROM mcr.microsoft.com/devcontainers/base:ubuntu
ENV CHOKIDAR_USEPOLLING=true

USER vscode
SHELL ["/bin/bash", "-lc"]
RUN curl -fsSL https://moonrepo.dev/install/proto.sh | bash -s -- --yes
RUN proto install bun
