# `basic-file-server`

Quickly create a basic HTTP file server for the current directory.

## Building the image

```bash
docker build . -t sidroberts/basic-file-server
```

## Usage

```bash
bin/basic-file-server
```

By default, the website will be hosted on port 80.
You can specify a custom port as the first argument:

```bash
bin/basic-file-server 8080
```
