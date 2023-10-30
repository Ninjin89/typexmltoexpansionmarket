# Type.xml to Expansion Market converter


Quick made this tool, maybe there will be updates coming & source release.
If something is not working let me know maybe i can update the tool for you.

## :rocket: Contact
<a href="https://discord.gg/mEPT9KNSxs"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

**SOURCE REPO** (make your own changes):
https://github.com/Ninjin89/TypesToExpansionMarket-Source

**Version 1.0.1**

This tool will export items out of type.xml by dragging the types.xml, on the .exe or double click the .exe while the type.xml is in same folder and is also named types.xml.

Also keep in mind the converter exports each item seperated, which means if you have for example: `watterbottle_green` and `watterbottle_blue` it will outprint it as each seperated codeblock and won't be listed under `variants` in the `TraderConfig.json`. You have todo that manually.

# How to use it
1.Place `types.xml` file into your Folder where the `convertertoexpansion.exe` is and run the exe. 
* yourtypes.xml must be named `types.xml`

2.Open the `TraderConfig.json` to see the output.


## Make sure the XML Heading is looking like in the Example.xml some Mod XML's do not have that which is bad!
<?xml version="1.0" encoding="utf-8"?>


**Changes you may also need to change to your liking:**

* DisplayName
* InitStockPercent
* Icon
* Color 
* Prices
* m_Version:

# Example of Xml

![image](https://user-images.githubusercontent.com/25750563/160250408-d90d7120-e276-4668-99f1-e5503b0db9a3.png)

		
## Example of the Json output
![image](https://user-images.githubusercontent.com/25750563/160250390-6f95d0b2-e081-4391-8f75-a9945d3bf9c0.png)



