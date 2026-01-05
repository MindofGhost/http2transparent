# http2transparent
A way to convert http/socks5 proxy to transparent proxy(youtubeUnblock)

## How to run it
1. Clone this repository and move all files to /opt/data/youtubeUnblock (you can chose another path, but don't forget to fix links)
2. Download youtubeunblock binary to /opt/data/youtubeUnblock
3. Run
```
ln -s /opt/data/youtubeUnblock/youtubeUnblock.service /lib/systemd/system/youtubeUnblock.service
systemctl daemon-reload
systemctl enable youtubeUnblock.service
systemctl start youtubeUnblock.service
docker compose up -d
```
