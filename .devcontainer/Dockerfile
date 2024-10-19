# Use universal dev container as base image
FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Install LaTeX dependencies
RUN apt-get update && \
    apt-get install -y texlive-full && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*