## Search PID using port number 

```bash
sudo ss -lptn 'sport = :8200' 

sudo netstat -nlp | grep :80

sudo lsof -n -i :80 | grep LISTEN
```
## Multipass set memory and cpu

```
multipass set local.primary.cpus=4
multipass set local.primary.memory=8G
multipass set local.primary.disk=10G
```

## Multipass set mount location
```
multipass mount /Users/rahulwagh/Documents/Documents-Rahul-MacBook-Pro/common-work-directory primary:/home/ubuntu/common-work-directory
```

```
## Delete Multipass

```
sudo chmod 755 /Library/Application\ Support/com.canonical.multipass/uninstall.sh

sudo /Library/Application\ Support/com.canonical.multipass/uninstall.sh
```

## Delete multipass with all data
```
brew uninstall --zap multipass
```

## Multipass : launch failed: cannot connect to the multipass socket

```
Kill the multipassd process form the process monitor 
```
