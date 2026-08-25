### HOW TO USE PLACEFILTERS
First thing you have to do is find a fast flag, in this example I will use ```DFFlagAddPlaceStats``` but any fast flag should work.
When you get your Fast flag, at the end of it type ```_PlaceFilter``` for my example, it would be ```DFFlagAddPlaceStats_PlaceFilter```.
Next, at the end of your values, type ```;PLACEID``` (Edit PLACEID to a game id) for mine, it would be ```DFFlagAddPlaceStats_PlaceFilter": "true;12345```

### MULTIPLE PLACES
Simply, just type ```;PLACEID``` for another place ontop of the other filter. For example, ```DFFlagAddPlaceStats_PlaceFilter": "true;12345;22433```

### ANNOYANCES
For ```FStringDebugShowFlagState``` you can only use placefilters for ALL of the fast flags instead of being able to make SOME only visible in certain games, which can get annoying QUICK if you are trying to debug something without twenty other fast flags showing at the same time.

### EXTRAS
For a fake channel name in roblox, use this fflag list and edit the value of ```DFStringChannelName``` to whatever you want.
```json
{
    "DFStringChannelName": "channelname",
    "FStringDebugShowFlagState": "DFStringChannelName"
}
```
### KNOWN SUPPORT
Injectors that are **NOT** sensitive on values.
### [FLEASION (GITHUB)](https://github.com/fleasion/Fleasion/releases)
### [FLEASION (ALTERNATIVE LINK)](https://fleasion.github.io/)
### [FIDDLER EVERYWHERE (PAID)](https://www.telerik.com/download/fiddler/fiddler-everywhere-windows)
### [FIDDLER EVERYWHERE (CRACKED VERSION)](https://github.com/NoobLikesThis/fiddler-everywhere-patch-automated/releases/download/frsss/Fiddler-Everywhere-V7.8.0-Patched.zip)
### [XSDR INJECTOR (BUGGY)](https://github.com/creatornawaf/XSDR-Injector/releases)
