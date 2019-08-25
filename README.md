# GetIPbyName
Get IP Address from a given Host Name in RPGLE

This utility might be useful for RPG/IBMi developers transitioning into modernized application eg consuming or providing web/mobile/cloud services within IBMi platform.

Parameters interface:

  pHostName - 100 char input parm expecting the Host Name, eg www.google.com
  
  pIPAddr - 50 char output parm to contain equivalent IP address (ie dotted form eg 123.456.789.0)
  
Tech Note: i used ActGrp(*New) but if you think it might slow down your app, feel free to use other option.

btw, thanks to Scott-Klement for his articles, without them this will be painful to do.
