CensorUrt plugin for Big Brother Bot (www.bigbrotherbot.net)
============================================================

Copyright 2010 courgette@bigbrotherbot.net



Description
-----------

This plugin extends the original censor plugin with the ability to mute and
slap players instead of giving them warning tickets.
This plugin is meant to work for Urban Terror servers.


Changelog
---------

21/10/2008 0.1.1
 - extends Censor plugin v2.1.0
 - move added mute code from xlr8or to that new plugin
 - changed _muteonly to _warnafter, so after a defined number of mute, the client get warned

22/10/2008 0.1.2
 - added slap function


Installation
------------
 
 * copy censorurt.py into b3/extplugins
 * disable the censor plugin from your main b3 config files (those two plugins
   are not meant to work at the same time)
 * add to the plugins section of your main b3 config file : 
   <plugin name="censorurt" config="@b3/extplugins/conf/plugin_censorurt.xml" />


Support
-------

Support is only provided on www.bigbrotherbot.net forums on the following topic :
http://www.bigbrotherbot.net/forums/index.php?topic=2276.0

