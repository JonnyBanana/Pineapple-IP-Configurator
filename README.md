# Wifi-Pineapple-IP-Configurator

<h3>A Windows Utility to Help to Setup Network for Wifi Pineapple Devices</h3>


<BR>

![Alt text](https://raw.githubusercontent.com/JonnyBanana/Pineapple-IP-Configurator/master/IMG/FondOrnateHellbender-small.gif)

<BR>


<h4>What does the program do?</h4>

In my experience I had to set up my Wifi Pineapple many times, sometimes due to the need to install it on different devices,
others because the network parameters were mysteriously forgotten by Windows, and it also happened to me simply by 
disconnecting the Wifi Pineapple from the USB port.
Every time you have to enter the IPv4 network parameters and reset the correct address,  and in the long run it can become frustrating ...

Hence the need to write a little script that did these simple maneuvers automatically.

The program is written in DOS for backward compatibility with Windows systems.

<BR>
 
![Alt text](https://raw.githubusercontent.com/JonnyBanana/Pineapple-IP-Configurator/master/IMG/pineapple-menu.PNG)
  
<BR>
  
Essentially the program has only 4 functions:

1. DISABLE DHCP: this function removes the dhcp from the Wifi Pineapple network (which must be named "WIFI_PINEAPPLE"), and
set as p IP address 172.16.42.42 and as Subnet Mask 255.255.0.0, thus allowing correct network operation for the Pineapple AP

2. RE ENABLE DHCP: this function resets the dhcp from the Wifi Pineapple network (which must be named "WIFI_PINEAPPLE"), 
it is useful when you have network problems, for troubleshooting

3. RENAME THE NETWORK: this function renames the network of the device in "WIFI_PINEAPPLE", it is used to make the program functions "1" and "2" work.

4. OPEN THE WIFI PINEAPPLE DASHBOARD: this function opens the web page of the Wifi Pineapple Dashboard (http://172.16.42.1:1471/#!/modules/Dashboard), 
to do this use the default browser, it is useful to open the interface once network problems are resolved or setup is complete

<BR>

<h4>Requirements</h4>

-The Network MUST be named "WIFI_PINEAPPLE" (u can use the function "3" of this utility)

-Admin Privileges

<BR>
 

You can also download an exe from here:

https://github.com/JonnyBanana/Wifi-Pineapple-IP-Configurator/releases/tag/wifipineapple

<BR>

Remember that if you need to set up Wifi Pineapple you must still enable internet connection sharing from the network properties.

Full setup guide here:

https://www.coengoedegebure.com/setting-up-wifi-pineapple/




</BR>
<!-- Banner -->
<div align="center">
<a href="https://www.purevpn.com/order-now.php?aff=44922&amp;a_bid=bbd0f893" target="_blank" ><img src="https://affiliates.purevpn.com/accounts/default1/6hb82wqa2l/bbd0f893.jpg" alt="Best VPN" title="Best VPN" width="728" height="90" /></a>
</BR></BR>
</div>







