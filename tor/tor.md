# install tor on macosx
brew install tor
brew services start tor

# check if you can tor out with curl
curl --socks5-hostname localhost:9050 https://check.torproject.org/api/ip
