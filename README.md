# ip-blacklist-collection
These are IP address blacklist you can use to fetch and parse and put in your firewall, waf, null-routing, sinkhole or what ever you choose. The blacklists are not necessary threat actors, it's just lists i like to have ready and handy.

# Revamp !
I want to ake some changes and re-do many fo the automated scripts that update this repo. Here is my todo list that i want to implement over the next period.
- Propper GEO reliant info (it often fails and are not correct)
- Propper AS Number information (it often fails and re not correct)
- Many scripts "deletes" all files before rebuilding them, leading to bad git history, only update what has changed in the future
- Better automation / solution to fetch lists and parse them
- Dont do TXT files but CSV in stead and add description/info as col 2 this will make it copatible with many lookup tables also
- Perhaps also leave txt files for backwards compatability if anyone uses them directly
  
