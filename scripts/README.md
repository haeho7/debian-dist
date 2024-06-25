# Scripts

## InstallNET.sh

It can reinstall `Debian`、 `Ubuntu`、`CentOS` system with network.

Default root password: `MoeClub.org`

```sh
# Debian 10 buster
./InstallNET.sh -d buster -v amd64 -p <password> --ip-addr <ip-addr> --ip-gate <ip-gate> --ip-mask <ip-mask>

# Debian 11 bullseye
./InstallNET.sh -d bullseye -v amd64 -p <password> --ip-addr <ip-addr> --ip-gate <ip-gate> --ip-mask <ip-mask>

# Debian 12 bookworm
bash <(wget -qO- "https://raw.githubusercontent.com/MoeClub/Note/master/InstallNET.sh") \
  -d bookworm \
  -v amd64 \
  -p <password> \
  --ip-addr <ip-address> \
  --ip-gate <ip-gateway> \
  --ip-mask <ip-netmask> \
  --mirror "http://deb.debian.org/debian"
```

## Reference

- [@MoeClub/Note/InstallNET.sh](https://github.com/MoeClub/Note/blob/c345a3fb8c15e9927d2f0e62cf74d50728bda10d/InstallNET.sh)
- [@moeclub.org/LinuxShell/InstallNET.sh](https://moeclub.org/attachment/LinuxShell/InstallNET.sh)
