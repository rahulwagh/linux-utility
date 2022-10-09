## Search PID using port number 

```bash
sudo ss -lptn 'sport = :8200' 

sudo netstat -nlp | grep :80

sudo lsof -n -i :80 | grep LISTEN
```