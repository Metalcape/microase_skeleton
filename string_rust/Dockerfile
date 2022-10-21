FROM rust:1.31

WORKDIR /src/myapp
COPY . .

RUN cargo install --path .

CMD ["string_rust"]