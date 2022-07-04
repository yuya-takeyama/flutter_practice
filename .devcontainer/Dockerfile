FROM mcr.microsoft.com/vscode/devcontainers/base:0-ubuntu-22.04

RUN apt update && \
    apt install -y tig tmux vim xz-utils \
      clang cmake ninja-build pkg-config libgtk-3-dev liblzma-dev # for Flutter
RUN curl --fail -L https://storage.googleapis.com/flutter_infra_release/releases/stable/linux/flutter_linux_3.0.4-stable.tar.xz \
  | tar -xvJf - -C /opt
