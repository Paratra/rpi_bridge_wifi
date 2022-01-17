# rpi_bridge_wifi

For hidden wifi bridging:

<1> 
Plug in two USB WiFi dongle into Raspberry Pi. Any plugged and go USB WiFi dongle will do. Such as this one. https://www.amazon.com/LOTEKOO-150Mbps-Adapter-Wireless-Raspberry/dp/B06Y2HKT75/ref=sr_1_3?keywords=usb+wifi+for+raspberry+pi&qid=1641999099&sprefix=USB+wifi+for+r%2Caps%2C59&sr=8-3 


<2>
Install a standard Raspberry Pi image onto the SD card; 


<3>
In Rpi system, running the bash script as:
'Usage: sudo ./ap_setup_script_hidden.sh wifi_username wifi_password hotspot_username hotspot_password'


For EDU wifi:

<1> 
Same as for hidden wifi

<2>
Same as for hidden wifi

<3>
In Rpi system, running the bash script as:
'Usage: sudo ./ap_setup_script_edu.sh edu_wifi_ssid edu_wifi_identity edu_wifi_password hotspot_username hotspot_password'

Reference:
https://inrg.soe.ucsc.edu/howto-connect-raspberry-to-eduroam/ 
