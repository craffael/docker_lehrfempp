FROM gcc:7.3.0

ADD https://cmake.org/files/v3.11/cmake-3.11.1-Linux-x86_64.tar.gz /cmake/
RUN cd /cmake && tar --strip-components=1 -xzf cmake-3.11.1-Linux-x86_64.tar.gz


ENV PATH="/cmake/bin:${PATH}"
