# lgtv-webos-domoticz-plugin
LG TV WebOS 3 Plugin for Domoticz


Steps for installation on Raspberry Pi for dummies:

Go to Plugins, create dir and clone git to dir:
<code>$cd domoticz/plugins/
$mkdir LGTV
$git clone https://github.com/GameDevHobby/Domoticz-LGTV-WebOS-Plugin.git LGTV
</code>

Go to dir and start using the plugin, install pylgtv
<code>$cd LGTV/
$chmod -x plugin.py
$sudo pip3 install pylgtv</code>

Always restart domoticz after new plugin
<code>$sudo service domoticz restart</code>

Log in to Domoticz and enable LG TV in Hardware tab.
Fill in the IP Address and MACaddress of the LG TV.
Turn on the TV via Domoticz, a popup on the tv will appear for 1 second you need to accept. Be quick with the remote!
