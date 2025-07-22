# TLS HTTPS Request Tool (GoLang)

## What it does:
This tool sends HTTPS GET requests using fake TLS fingerprints (like Chrome/Firefox/Safari) and rotates proxies to bypass anti-bot protections like Cloudflare.

## How to use:

1. Install Go (https://go.dev/doc/install)

2. In terminal, go into the project folder:

```
go get github.com/refraction-networking/utls
go build -o tls-scraper main.go
./tls-scraper
```

3. Make sure you added working proxies in `proxies.txt`

4. Set your settings in `config.json` and run the tool.

That’s it!