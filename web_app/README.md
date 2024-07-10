## Get started

### Cargo

Running the web app with cargo
`cargo run`

Other helpful cargo comands
`cargo clean`
`cargo build`

## Installing Diesel

https://diesel.rs/guides/getting-started
`curl --proto '=https' --tlsv1.2 -LsSf https://github.com/diesel-rs/diesel/releases/download/v2.2.1/diesel_cli-installer.sh | sh`
`cargo install diesel_cli --no-default-features`

### Running migrations

`diesel migration generate create_to_do_items`

## Docker

Inspecting docker database
`docker exec -it <container ID> psql -U username to_do`

### Exit docker

press Ctrl+D to exit and stop the container.

## PQ

`cargo install pq`
