FROM fedora
LABEL maintainer="mijo.safradin@googlemail.com" 
RUN curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs -sSf > rustup.rs && sh rustup.rs -y
ENV PATH /root/.cargo/bin:$PATH
ENV USER rusty
