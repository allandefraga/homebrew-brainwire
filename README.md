# Brainwire Homebrew tap

Install the experimental macOS CLI from source:

```sh
brew install allandefraga/brainwire/brainwire
brainwire --version
brew test allandefraga/brainwire/brainwire
```

The first build compiles Rust and RocksDB and may take several minutes.
Homebrew installs build dependencies as needed. The formula currently pins
Brainwire v0.24.0-beta.2. It has been tested on Apple Silicon; Intel macOS
has not been verified. For server, Python and Docker instructions, see the
[Brainwire documentation](https://allandefraga.github.io/brainwire/).
