## Acutrite smartHUB bridge with nodered 
With the help of https://github.com/billfor/acurite-bridge I was able to recreate the hub-bridge to get my acurite 5-1 weather station to upload to weatherundgerground.


### Requirements
- Node Red running and able to listen on port 80 (either start nodered on port 80 or use ngnix/apache to redirect 80 to nodered port 1880)
- dnsmasq or another way to hijack DNS responses for hupapi.myacurite.com
- Bridge Device ID (from the bottom of your smartHUB)
- Station ID and KEY from Weather Underground

### Installation
- Import Flow into Nodered
- edit "check device ID, add ID and Key" node to your PWS ID and Key from your device profile on weatherunderground.com
