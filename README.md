Z390 AORUS PRO WIFI HACKINTOSH

# Hackintosh Reference Guide - Gigabyte Z390 Aorus Pro WiFi (Dual-Boot W7/Catalina)

### Hardware

Type|Item
:----|:----
**CPU** |[Intel - Core i9-9900k](https://www.google.com/search?q=intel+i9+9900k&oq=intel+i9+9900k&aqs=chrome..69i57j0l7.6112j0j7&sourceid=chrome&ie=UTF-8)
**CPU Cooler** |[NZXT Kraken x72](https://www.google.com/search?sxsrf=ALeKk01rc9oG02qpaqgyVy4rSe-dM_xKDw%3A1585447671952&ei=9wKAXtTgOc3WtAaV6bOACQ&q=nzxt+kraken+x72&oq=nzxt+kra&gs_lcp=CgZwc3ktYWIQARgBMgQIIxAnMgUIABCRAjIFCAAQkQIyCggAEIMBEBQQhwIyBAgAEEMyBwgAEBQQhwIyBQgAEIMBMgIIADICCAAyAggAOgQIABBHULcTWNYuYIE8aANwA3gAgAG2CYgBxheSAQ0wLjEuNC0xLjIuMC4xmAEAoAEBqgEHZ3dzLXdpeg&sclient=psy-ab) 
**Motherboard** | [Gigabyte - Z390 AORUS PRO WiFi](https://shopee.com.my/product/18799831/1830724338)
**Memory** | [Corsair Vengeance RGB 4x8GB](https://www.google.com/search?sxsrf=ALeKk00ypf0eSWDMoLR2dXSoWzNEeZUoBw%3A1585448934617&ei=5geAXq6jJduqtQaIg4roDg&q=corsair+vengeance+rgb&oq=corsair+vengeance+rgb&gs_lcp=CgZwc3ktYWIQAzIHCAAQFBCHAjICCAAyAggAMgIIADICCAAyAggAMgIIADICCAAyAggAMgIIAFD1xgJY9s0CYJLUAmgAcAB4AIABugqIAbwckgEJNC0xLjEuMC4ymAEAoAEBqgEHZ3dzLXdpeg&sclient=psy-ab&ved=0ahUKEwiurrrE0b7oAhVbVc0KHYiBAu0Q4dUDCAs&uact=5)
**Storage** | [Samsung 970 Evo Plus 500GB + 2TB HDD](https://www.google.com/search?sxsrf=ALeKk03f5iS-k1aUfq2qOX5BZKaYIxdJ5A%3A1585447765138&ei=VQOAXr-DCNnRtAaN36_IAg&q=Samsung+970+Evo+Plus+500GB&oq=Samsung+970+Evo+Plus+500GB&gs_lcp=CgZwc3ktYWIQAzICCAAyAggAMgYIABAIEB4yBggAEAgQHjIGCAAQCBAeMgYIABAIEB4yBggAEAgQHjIGCAAQCBAeMgUIABDNAjIFCAAQzQI6BAgAEEc6BggAEAcQHjoICAAQCBAHEB5Q2LoBWIvoAWCc7QFoAHACeACAAfsIiAHwKJIBDTAuMi4xLjEuNi0xLjOYAQCgAQGqAQdnd3Mtd2l6&sclient=psy-ab&ved=0ahUKEwj_geeWzb7oAhXZKM0KHY3vCykQ4dUDCAs&uact=5)**Video Card** | Radeon RX 580 8 GB (about:blank)
**WiFi + Bluetooth** | [TP Link T6 Archer](https://www.google.com/search?sxsrf=ALeKk03myLcsAbUj3mdOLpnb2KmdhluryA%3A1585447944900&ei=CASAXvnDNpjStQbpnKLwBA&q=tp+link+t6+archerwifi+card&oq=tp+link+t6+archerwifi+card&gs_lcp=CgZwc3ktYWIQAzoECAAQRzoHCCMQsAIQJzoECAAQDToHCAAQFBCHAjoCCAA6BggAEAcQHjoICAAQCBAHEB46BQgAEM0COgQIIRAKUJQqWLVaYOdeaABwA3gAgAHTBYgB5x6SAQ0wLjMuNC4xLjIuMS4xmAEBoAEBqgEHZ3dzLXdpeg&sclient=psy-ab&ved=0ahUKEwj558Lszb7oAhUYac0KHWmOCE4Q4dUDCAs&uact=5)
**Case** | [Thermaltake P3](https://www.google.com/search?q=Thermaltake+P3&oq=Thermaltake+P3&aqs=chrome..69i57j35i39j0l6.627j0j9&sourceid=chrome&ie=UTF-8)
**Power Supply** | [PowerSpec 850W](https://www.google.com/search?sxsrf=ALeKk0305HFlW6lfHMq-_NQCmiUlt-oFOA%3A1585448044678&ei=bASAXqeIKdq3tAbjt6_wDA&q=powerspec+850w+rgb&oq=opwerspec+850+w&gs_lcp=CgZwc3ktYWIQAxgAUABYAGC0EWgAcAB4AIABAIgBAJIBAJgBAKoBB2d3cy13aXo&sclient=psy-ab)



### Step By Step Installation Guide

[STEP_BY_STEP.md](STEP_BY_STEP.md)

### USB Configuration

[USBMAP.md](USBMAP.md)

### What's Working/What's Not

##### Working
- Ethernet
- Onboard Audio
- HDMI Audio
- DP Audio
- IGPU in headless mode
- App Store
- Wake/Sleep
- Restart
- Shutdown
- USB (Correct SS/HS speed)
- All DP and HDMI port
- iMessage
- Facetime
- Handoff
- Airdrop
- Continuity
- AirPlay
- Encryption
- MacOs Native Apps (IntelliJ, FL Studio, Photos, etc)

##### Not Working
- Built-in WiFi and Bluetooth. This will never work, dont even waste time here. Purchased the TP Link T6 Archer and it was plug-and-play, still need to get bluetooth card/usb

### Caveat
- After first reboot, the installer might be stuck at `About 13/15 minutes remaining...`. Don't be alrmed, just give it 5 ~ 10 min, it will eventually work again. Your mouse and keyboard most probably wont be working in this installation stage
- If you encounter the error below, just clear your BIOS via motherboard
- If you get an error with a Prohibited Sign instead of an Apple logo, Inject Graphics on Clover Bootloader.
	```
	Error allocating 0x1197b pages at xxx alloc type x
	Couldn't allocate runtime area
	```


### Changelog

- 03-28-2020: Everything still works. Making optimizations - Changed SATA SSD to NVMe SSD 
