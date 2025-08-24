FROM tensorflow/tensorflow:2.15.0-gpu

ENV DEBIAN_FRONTEND=noninteractive

# Utilidades basicas
RUN apt-get update && apt-get install -y \
    git wget curl vim htop && \
    rm -rf /var/lib/apt/lists/*
