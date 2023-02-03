# HOW TO USE IT

## 1 Checkout poject

```shell
git clone https://github.com/davydes/tor.git
cd tor
```

## 2 Build image

```
docker-compose build
```

## 3 Get obfs4 bridge lines

1. Goto: https://bridges.torproject.org/options/ and get bridges.
2. Place all bridge lines to file torrc: each line place as `Bridge <line>`
3. Save torrc file

## 4 Run it

```shell
docker-compose up -d
```

## 5 Make sure that it's working

```shell
docker-compose logs --follow
```

You have to see that bootstap completed!

Press `Ctrl+C` to stop watch logs

## 6 Configure socks proxy

Use proxy address `127.0.0.1:9050`
