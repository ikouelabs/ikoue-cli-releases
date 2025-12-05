# Ikoue Academy CLI

Developer CLI helper for the Ikoue Academy program.

## Installation

### macOS (Apple Silicon)

```bash
curl -L https://github.com/ikouelabs/ikoue-cli-releases/releases/latest/download/ikoue_darwin_arm64.tar.gz | tar xz
sudo mv ikoue /usr/local/bin/
```

### macOS (Intel)

```bash
curl -L https://github.com/ikouelabs/ikoue-cli-releases/releases/latest/download/ikoue_darwin_amd64.tar.gz | tar xz
sudo mv ikoue /usr/local/bin/
```

### Linux (x86_64)

```bash
curl -L https://github.com/ikouelabs/ikoue-cli-releases/releases/latest/download/ikoue_linux_amd64.tar.gz | tar xz
sudo mv ikoue /usr/local/bin/
```

### Linux (ARM64)

```bash
curl -L https://github.com/ikouelabs/ikoue-cli-releases/releases/latest/download/ikoue_linux_arm64.tar.gz | tar xz
sudo mv ikoue /usr/local/bin/
```

### Windows

Download `ikoue_windows_amd64.zip` from [releases](https://github.com/ikouelabs/ikoue-cli-releases/releases/latest), extract, and add to your PATH.

## Verify Installation

```bash
ikoue version
```

## Updating

The CLI automatically checks for updates once per day. When a new version is available, you'll see:

```
A new version is available: x.x.x
Run 'ikoue self-update' to update
```

To update:

```bash
ikoue self-update
```

## Usage

```bash
ikoue --help
```
