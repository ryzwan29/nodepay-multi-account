# Nodepay Auto Farming
Feature:
- Can running with proxy or Without proxy
- Can mining multi account

### Requirements
- Python3.10 or higher
- Pip3
- Python Environment

# Setup Tutorial
- Open [Nodepay](https://app.nodepay.ai/register?ref=ZUCBuJaIoBXLE6J) and login to dashboard
- Right click and **inspect**
- Select Console
```
localStorage.getItem('np_token')
```
⚠️ If you can't paste in the console, please type manually ```allow pasting```

# Installation
```
source <(curl -s https://raw.githubusercontent.com/ryzwan29/nodepay-multi-account/main/quick-installation.sh)
```

#### Run command
✅ If you're using a proxy
```
python3 run_proxy.py
```
⚠️ If you're not using a proxy
```
python3 noproxy.py
```

# Format Proxy
- http://ip:port
- http://user:pass@ip:port

# Source : https://github.com/im-hanzou

