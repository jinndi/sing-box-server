<p align="center">
  <img alt="sing-box-server" src="/logo.webp" width="180">
</p>
<h1 align="center">
  sing-box-server
</h1>
<h3 align="center">
The fastest way to get a connection link to the sing-box server
</h3>

<p align="center">
<img alt="Release" src="https://img.shields.io/github/v/release/jinndi/sing-box-server">
<img alt="Code size in bytes" src="https://img.shields.io/github/languages/code-size/jinndi/sing-box-server">
<img alt="License" src="https://img.shields.io/github/license/jinndi/sing-box-server">
<img alt="Visitor" src="https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2Fjinndi%2Fsing-box-server&label=visitor&icon=eye&color=%230d6efd&message=&style=flat&tz=UTC">
</p>

## 🚀 Features

- Obtaining the protocol link for connection after installation
- Configuring SSL certificates via ACME or by specifying a local path
- Setting and changing the masking domain for TLS Reality
- Switching protocol and port via the management script
- Regenerating the connection link
- Checking and updating the sing-box core when entering the management script
- Optimized network settings via sysctl

## 🌐 Supported protocols

Without SSL configuration:

- Shadowsocks2022-TCP-UDP
- Shadowsocks2022-TCP-Multiplex
- VLESS-TCP-XTLS-Vision-REALITY
- WireGuard

If SSL is configured + :

- VLESS-TCP-XTLS-Vision
- VLESS-TCP-TLS-Multiplex
- Trojan-TCP-TLS
- Trojan-TCP-TLS-Multiplex
- Hysteria2
- TUIC

## 📋 Requirements

- Debian/Ubuntu-based systems
- Curl installed
- You need to have a domain name or a public IP address

## 💾 Installation

Install it with the following command:

```
sudo bash <(curl -Ls https://raw.githubusercontent.com/jinndi/sing-box-server/main/install.sh)
```

The script installs into `/opt/sing-box`, and you can control them using the `sing-box` command.
