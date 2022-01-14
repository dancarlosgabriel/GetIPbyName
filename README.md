# GetIPbyName
Get IP Address of a given Host Name in RPGLE

This utility might be useful for RPG/IBMi developers transitioning into modernized application eg consuming or providing web/mobile/cloud services within IBMi platform.

Parameters interface:

  pHostName -- 100-char input parm - to pass the Host Name to find IP address for eg www.google.com
  
  pIPAddr -- 50-char output parm - to contain the returned IP address (ie in dotted form eg 123.456.789.0)
  
Tech Note: used compil option ActGrp(*New), but feel free to use other option that suits you. 

BTW, thanks to Scott-Klement for his articles, it's been a useful reference.
