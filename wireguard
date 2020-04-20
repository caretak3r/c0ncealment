# I don't trust APP store GUIs, so I am mimicking linux install + setup
mkdir -p /usr/local/etc/wireguard
cd /usr/local/etc/wireguard
umask 077

# generate private key
wg genkey > private.key
wg pubkey < private.key > public.key

# register your private key and shasum512 hash for token with an appropriate provider

# then use the quick setup once you have your openvpn conf files and desired location
wg-quick up cn-somewhereinChina

# you should check for DNSleaking and/or host info
