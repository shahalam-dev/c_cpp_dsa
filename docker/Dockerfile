FROM alpine:latest

# Install build tools and C/C++ development packages
RUN apk add --no-cache \
    build-base \
    cmake \
    make \
    gcc \
    g++ \
    clang \
    gdb \
    valgrind \
    git \
    bash \
    vim \
    nano

# Set working directory
WORKDIR /app

# Command to run when container starts
CMD ["/bin/bash"]