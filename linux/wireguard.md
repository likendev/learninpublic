# Setting up WireGuard in Fedora

## Installing WireGuard
```bash
sudo dnf install wireguard-tools
```

## Configuring the WireGuard interface
```bash
sudo touch /etc/wireguard/wg0.conf
```

## Update the WireGuard interface config
```bash
sudoedit /etc/wireguard/wg0.conf
```
```
[Interface]
PrivateKey = <Your Private Key>
Address = <Your Ip Address>

[Peer]
PublicKey = <PeerPublicKey>
AllowedIPs = 0.0.0.0/0
Endpoint = <PeerEndpoint>:51820
```

## Enabling and Starting the WireGuard Service
```bash
sudo systemctl enable wg-quick@wg0
sudo systemctl start wg-quick@wg0
```

## Verifying the Connection
```bash
sudo wg show
```
