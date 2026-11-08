# Part 3: Deploying Linux Server (VM Setup, Services & Connectivity Testing)

## 1. Nginx Package Installation
```bash
sudo apt update
sudo apt install nginx -y```

Starting and enabling the web service daemon:
```bash
sudo systemctl enable --now nginx
sudo systemctl status nginx```
