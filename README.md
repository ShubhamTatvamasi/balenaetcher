# balenaetcher

1. Add Etcher Debian repository:
```sh
curl -1sLf \
  'https://dl.cloudsmith.io/public/balena/etcher/setup.deb.sh' \
  | sudo -E bash
```

2. Update and install:
```sh
sudo apt-get update
sudo apt-get install balena-etcher-electron
```
