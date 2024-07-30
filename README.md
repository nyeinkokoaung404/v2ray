# Introduction

The best V2Ray one-click installation script &amp; management script

# Features

- Quick installation
- Super easy to use
- Zero learning cost
- Automatic TLS
- Simplify all processes
- Block BT
- Block Chinese IP
- Use API operation
- Compatible with V2Ray commands
- Powerful shortcut parameters
- Support all common protocols
- One-click to add Shadowsocks
- One-click to add VMess-(TCP/mKCP/QUIC)
- One-click to add VMess-(WS/H2/gRPC)-TLS
- One-click to add VLESS-(WS/H2/gRPC)-TLS
- One-click to add Trojan-(WS/H2/gRPC)-TLS
- One-click to add VMess-(TCP/mKCP/QUIC) dynamic port
- One-click to enable BBR
- One-click to change the disguised website
- One-click to change (Port/UUID/Password/Domain Name/Path/Encryption Method/SNI/Dynamic Port/etc...)
- And many more...

# Design Concept

Design Concept: **High Efficiency, Super Fast, Extremely Easy to Use**

The script is based on the author's own usage needs, with **Multiple Configurations Running Simultaneously** as the core design

And it is specially optimized for the four common functions of adding, changing, viewing, and deleting

You only need one command to complete operations such as adding, changing, viewing, and deleting

For example, it takes less than 1 second to add a configuration! Adding is completed instantly! The same is true for other operations!

The script parameters are very efficient and super easy to use, please master the use of parameters

# Script description

[V2Ray one-click installation script](https://github.com/233boy/v2ray/wiki/V2Ray%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85%E8%84%9A%E6%9C%AC)

# Construction tutorial

[V2Ray construction detailed graphic tutorial](https://github.com/233boy/v2ray/wiki/V2Ray%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E5%9B%BE%E6%96%87%E6%95%99%E7%A8%8B)

# Help

Use: `v2ray help`

```
V2Ray script v4.21 by 233boy
Usage: v2ray [options]... [args]...

Basic:
v, version displays the current version
ip returns the IP of the current host
get-port returns an available port

General:
a, add [protocol] [args... | auto] adds configuration
c, change [name] [option] [args... | auto] changes configuration
d, del [name] deletes configuration**
i, info [name] views configuration
qr [name] QR code information
url [name] URL information
log views logs
logerr views error logs

Changes:
dp, dynamicport [name] [start | auto] [end] changes dynamic port
full [name] [...] changes multiple parameters
id [name] [uuid | auto] changes UUID
host [name] [domain] changes domain name
port [name] [port | auto] changes port
path [name] [path | auto] changes path
passwd [name] [password | auto] Change password
type [name] [type | auto] Change camouflage type
method [name] [method | auto] Change encryption method
seed [name] [seed | auto] Change mKCP seed
new [name] [...] Change protocol
web [name] [domain] Change camouflage website

Advanced:
dns [...] Set DNS
dd, ddel [name...] Delete multiple configurations**
fix [name] Fix a configuration
fix-all Fix all configurations
fix-caddyfile Fix Caddyfile
fix-config.json Fix config.json

Management:
un, uninstall Uninstall
u, update [core | sh | dat | caddy] [ver] Update
U, update.sh Update script
s, status Run status
start, stop, restart [caddy] Start, stop, restart
t, test Test run
reinstall Reinstall script

Test:
client [name] Display client JSON, for reference only
debug [name] displays some debug information, for reference only
gen [...] is the same as add, but only displays JSON content, does not create files, for testing purposes
genc [name] displays part of JSON for the client, for reference only
no-auto-tls [...] is the same as add, but prohibits automatic configuration of TLS, can be used for *TLS related protocols
xapi [...] is the same as v2ray api, but the API backend uses the currently running V2Ray service

Others:
bbr enables BBR, if supported
bin [...] runs V2Ray commands, for example: v2ray bin help
api, convert, tls, run, uuid [...] are compatible with V2Ray commands
h, help displays this help interface

Use del, ddel with caution, this option will directly delete the configuration; no confirmation is required
Feedback) https://github.com/233boy/v2ray/issues
Documentation (doc) https://233boy.com/v2ray/v2ray-script/ ```
