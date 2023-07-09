## Search PID using port number 

```bash
sudo ss -lptn 'sport = :8200' 

sudo netstat -nlp | grep :80

sudo lsof -n -i :80 | grep LISTEN
```

## Delete Multipass

```
sudo chmod 755 /Library/Application\ Support/com.canonical.multipass/uninstall.sh

sudo /Library/Application\ Support/com.canonical.multipass/uninstall.sh
```
