This is a fork from useragent. I created this mainly for my own use.
Refer to 3rd-Eden/useragent for more details.
3rd-Eden User Agent: https://github.com/3rd-Eden/useragent

2020-07-24
What i Modify:
1. Device to include brand and model.
2. Fix a bug where fs.rename will throw error if you are having /tmp in different volume/device.
3. Added some logs in updater function to let me know if the updater is working or not.
4. There are some $1 to $4 in some of the device family name, model or brand. so i try to make it replacable by correct variable.