# wireguard
## commands
- wg genkey >privkey.pem
- wg genpsk >psk.pem
- cat privkey.pem|wg pubkey > pubkey.pem
- wg-quick up wg0
- systemctl enable wg-quick@wg0
