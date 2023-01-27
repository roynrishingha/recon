<h1 align="center">recon</h1>

<p align="center">A port scanner cli for active reconnaissance</p>

## Usage

1. clone locally

```sh
git clone https://github.com/royrustdev/recon.git
cd recon
```

2. compile

```sh
cargo build --release
```
### List modules

```sh
cargo run -- modules
```

### Scan a target

```sh
cargo run --release -- scan <example.com>
```

## Example

```sh
./target/release/recon modules
./target/release/recon scan royrustdev.com
```

or

```sh
cargo run --release -- scan royrustdev.com
```