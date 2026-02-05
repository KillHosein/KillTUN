

```bash
bash <(curl -Ls https://raw.githubusercontent.com/KillHosein/VortexL2-main/main/install.sh)
```

## 🚀 First Run

### 1. Open the Management Panel

```bash
sudo killhosein
```


```bash
# Stop services
sudo systemctl stop vortexl2-tunnel
sudo systemctl disable vortexl2-tunnel

# Remove files
sudo rm -rf /opt/vortexl2
sudo rm /usr/local/bin/killhosein
sudo rm /etc/systemd/system/vortexl2-*
sudo rm -rf /etc/vortexl2

# Reload systemd
sudo systemctl daemon-reload
```
