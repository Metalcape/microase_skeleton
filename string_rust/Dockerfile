FROM rust:latest

ADD . /string_rust
WORKDIR /string_rust

RUN cargo install --path .

CMD ["string_rust"]