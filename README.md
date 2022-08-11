# Ro-Sniper-python

## How it works?

It uses roblox inventory api to get item price.
As it doesn't load catalog website it is faster than any other sniper programs.

## Requirements

Python >= 3.7, python-dotenv, requests

## .env Settings

```
TOKEN : Roblox auth token. (.ROBLOSECURITY on Roblox website)
THREADS : How fast you want (2~3 recommended)
PROFIT : If you set this to 1 program buy items which you can get over 100% profit
MAXTOPAY : Max to pay
```

## How to use

1. Create caches folder on sniper directory
2. Add your cookie to .env file
3. Put your http proxy into proxy.txt file
4. Add limited id you want to snipe to Limited_IDS.txt file
5. Enjoy !

## Proxy Information

You need Proxy IP and Port to use it.
This means you need to search for a "Proxy Server" urself. The recent I know https://geonode.com/free-proxy-list/

You can also rent your own private Proxy Server so its faster and safer to use.
Its still under your responsibility.

Remember it need to be http://

# Troubleshoot

### "Last 5min Checked 0, Last 5min Error0, Total Checks 0" fail

Check caches for fails---
Open the bat Pick option 1 and search the scan for fails.
Clear out the failing Limiteds in Limited_IDS.txt and delete the Cache attached to it.

### 'requests' module error
```
Traceback (most recent call last):
File "main.py", line 2, in ‹module>
import requests
ModuleNotFoundError: No module named 'requests'
```
Open CMD and type
```
pip install requests
```
