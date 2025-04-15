# Namecheap Scripts

## Install
```
./setup.sh
```

## Setup
1. Enable Namecheap API access from Profile -> Tools
2. Whitelist your IP: `curl https://ipinfo.io/ip`
3. Copy config.ini.example to config.ini
4. Fill in config.ini with USER, API_KEY, and IP
```
cp config.ini.example config.ini
vim config.ini
```

## Run
```
./listDomains
```

## Assumptions
* Domain price/cost based on renewal cost
* Domain price/cost not adjusted for changes
* Does not handle premium domains (yet)
