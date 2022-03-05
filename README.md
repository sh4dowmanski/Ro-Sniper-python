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

# Troubleshoot

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
