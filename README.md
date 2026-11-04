# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
```
Microsoft Windows [Version 10.0.26200.9711]
(c) Microsoft Corporation. All rights reserved.

1.IPCONFIG:
C:\Users\acer>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::b246:2d04:ced8:d3ed%14
   IPv4 Address. . . . . . . . . . . : 192.168.56.1
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . : saveetha.in
   IPv6 Address. . . . . . . . . . . : 2403:8600:c090:42:0:404:c975:9d98
   Link-local IPv6 Address . . . . . : fe80::504:d8bd:db91:71bd%9
   Autoconfiguration IPv4 Address. . : 169.254.250.194
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . : fe80::eedd:24ff:fe3d:ced5%9

Ethernet adapter Bluetooth Network Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

2.NETSTAT:
C:\Users\acer>netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    127.0.0.1:5141         TMP215-75-G2:56818     ESTABLISHED
  TCP    127.0.0.1:46935        TMP215-75-G2:63042     ESTABLISHED
  TCP    127.0.0.1:46936        TMP215-75-G2:49681     ESTABLISHED
  TCP    127.0.0.1:46937        TMP215-75-G2:49683     ESTABLISHED
  TCP    127.0.0.1:49669        TMP215-75-G2:49670     ESTABLISHED
  TCP    127.0.0.1:49670        TMP215-75-G2:49669     ESTABLISHED
  TCP    127.0.0.1:49674        TMP215-75-G2:49675     ESTABLISHED
  TCP    127.0.0.1:49675        TMP215-75-G2:49674     ESTABLISHED
  TCP    127.0.0.1:49676        TMP215-75-G2:49677     ESTABLISHED
  TCP    127.0.0.1:49677        TMP215-75-G2:49676     ESTABLISHED
  TCP    127.0.0.1:49678        TMP215-75-G2:49679     ESTABLISHED
  TCP    127.0.0.1:49679        TMP215-75-G2:49678     ESTABLISHED
  TCP    127.0.0.1:49680        TMP215-75-G2:49682     ESTABLISHED
  TCP    127.0.0.1:49681        TMP215-75-G2:46936     ESTABLISHED
  TCP    127.0.0.1:49682        TMP215-75-G2:49680     ESTABLISHED
  TCP    127.0.0.1:49683        TMP215-75-G2:46937     ESTABLISHED
  TCP    127.0.0.1:49685        TMP215-75-G2:49686     ESTABLISHED
  TCP    127.0.0.1:49686        TMP215-75-G2:49685     ESTABLISHED
  TCP    127.0.0.1:50467        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:56818        TMP215-75-G2:5141      ESTABLISHED
  TCP    127.0.0.1:57603        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:58422        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:50467     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:57603     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:58422     ESTABLISHED
  TCP    127.0.0.1:63040        TMP215-75-G2:63041     ESTABLISHED
  TCP    127.0.0.1:63041        TMP215-75-G2:63040     ESTABLISHED
  TCP    127.0.0.1:63042        TMP215-75-G2:46935     ESTABLISHED
  TCP    127.0.0.1:63045        TMP215-75-G2:63046     ESTABLISHED
  TCP    127.0.0.1:63046        TMP215-75-G2:63045     ESTABLISHED
  TCP    127.0.0.1:63047        TMP215-75-G2:63048     ESTABLISHED
  TCP    127.0.0.1:63048        TMP215-75-G2:63047     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:53100     TIME_WAIT
  TCP    [::1]:15161            TMP215-75-G2:53101     TIME_WAIT
  TCP    [::1]:15161            TMP215-75-G2:56817     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:56819     ESTABLISHED
  TCP    [::1]:56817            TMP215-75-G2:15161     ESTABLISHED
  TCP    [::1]:56819            TMP215-75-G2:15161     ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:49272  sh-in-f138:https       TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:49364  lcbomp-in-f84:https    TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:49469  [2603:1040:a06:6::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:49692  [2001:4860:4847:400::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:49811  [2603:1046:c04:1016::2]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:49922  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:49992  lcmaaa-ap-in-x06:https  FIN_WAIT_1
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:50019  [2001:4860:4828:7700::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:50167  [2001:4860:482d:7700::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:50312  pnmaaa-az-in-x03:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:50418  maa05s06-in-x01:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:50987  lcbomp-in-f84:https    TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:50997  [2403:8600:c090:42:a000::300]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51093  whatsapp-cdn6-shv-02-maa5:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51392  [64:ff9b::489a:766]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51397  a184-28-109-248:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51406  g2600-140f-0006-0000-0000-0000-1739-4b59:http  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51436  lcmaaa-as-in-x0a:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51866  [64:ff9b::3996:bf41]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51867  [2603:1040:a06:6::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51873  [64:ff9b::287e:1187]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51875  [2603:1046:c04:1048::2]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51876  [2603:1061:13f0:116::365:590]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51877  [2603:1046:c04:1048::2]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51879  [2603:1063:2001:190e::365:ff1]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51880  [2603:1046:c04:1405::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51884  [2620:1ec:50::11]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51886  [64:ff9b::287e:1187]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51896  [2603:1046:c04:1048::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51897  [2603:1046:c04:1048::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51922  a184-28-109-252:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51925  g2600-140f-0006-0000-0000-0000-1739-4b51:http  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:51931  [64:ff9b::287e:1187]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:52059  [2001:4860:4844:400::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:52134  [2620:1ec:33::11]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:52402  [2001:4860:4827:700::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:52633  lcmaaa-as-in-x0a:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:52713  sh-in-f119:https       TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:52730  ly-in-f94:https        TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:53090  [2001:4860:4846:400::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:53097  [64:ff9b::2854:6104]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:53294  lcmaaa-ap-in-x06:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:53757  [64:ff9b::d45:6d82]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:53785  a184-28-109-252:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:53917  [64:ff9b::496:df60]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:54038  lcmaaa-ao-in-x0e:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:54377  [2001:4860:4840:400::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:54463  [2603:1061:10::13]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:54466  [64:ff9b::d45:6d82]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:54531  lcmaaa-ap-in-x06:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:54693  [2001:4860:4847:400::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:54762  lcbomp-in-f84:https    TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:54937  lcmaaa-ap-in-x06:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:55072  [2001:4860:4829:700::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:55272  lcbomo-in-f138:https   TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:55677  [2001:4860:482b:400::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:55802  maa05s06-in-x01:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:56078  [2001:4860:4846:400::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:56866  [2603:1061:14:81::1]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:56920  g2600-140f-5e00-0014-0000-0000-17d3-3c26:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:56921  [2603:1063:2001:193f::365:ff1]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:56922  [2603:1047:1:98::80]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:57011  ly-in-f94:https        TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:57263  lcmaaa-as-in-x0a:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:57270  whatsapp-cdn6-shv-01-maa5:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:57314  pnmaaa-av-in-x03:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:57514  [64:ff9b::96ab:1b0a]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:57675  [64:ff9b::3384:c16d]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:57683  [64:ff9b::d45:6d82]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58015  [2001:4860:4827:7700::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58016  [2603:1061:14:82::1]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58050  [2603:1046:c04:104a::2]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58211  [2403:8600:c090:42:a000::300]:http  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58250  [2001:4860:4829:700::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58253  [64:ff9b::496:df67]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58254  lcmaaa-ap-in-x06:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58255  g2600-140f-0006-0000-0000-0000-17c7-4551:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58256  g2600-140f-0006-0689-0000-0000-0000-0ae0:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58257  g2600-140f-0006-0000-0000-0000-17c7-4551:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58258  [64:ff9b::287e:1187]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58259  [64:ff9b::287e:1187]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58568  pnmaaa-bf-in-x0e:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58601  whatsapp-cdn6-shv-03-maa3:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58608  [64:ff9b::287e:1187]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58612  [2001:4860:4847:400::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:58768  [2001:4860:482b:700::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:59196  ncboms-in-f113:https   ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:59216  lcboma-aw-in-x0e:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:59344  pnmaaa-bd-in-x0e:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:59489  maa05s20-in-x0e:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60005  g2600-140f-5e00-0005-0000-0000-17d3-3c6e:http  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60006  lcmaaa-az-in-x03:http  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60009  g2600-140f-5e00-01a6-0000-0000-0000-21cc:http  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60012  g2600-140f-5e00-0014-0000-0000-17d3-3c17:http  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60013  g2600-14e1-0018-006d-0000-0000-0000-0000:http  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60018  g2600-140f-5e00-0005-0000-0000-17d3-3c6e:http  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60261  hkg12s32-in-f2:https   ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60267  g2600-140f-5e00-0882-0000-0000-0000-0057:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60291  lcmaaa-as-in-x0a:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60728  lcmaaa-as-in-x0a:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60729  [2603:1061:14:82::1]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60791  pnmaaa-az-in-x03:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:60994  whatsapp-cdn6-shv-02-maa3:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61000  whatsapp-cdn6-shv-03-maa3:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61005  whatsapp-cdn6-shv-02-maa5:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61009  si-in-f188:https       ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61010  [2603:1061:14:83::1]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61011  [64:ff9b::496:df60]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61012  bingforbusiness:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61013  a23-223-42-238:http    TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61015  [64:ff9b::496:df69]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61031  [2001:4860:482b:400::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61034  [2001:4860:4847:400::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61169  [2001:4860:482b:700::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61211  server-108-159-15-70:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61212  [2001:4860:482c:400::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61357  whatsapp-cdn6-shv-01-maa3:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61733  [2403:8600:c090:42:a000::300]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61798  lcmaaa-as-in-x0a:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:61968  [64:ff9b::d45:6d82]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62125  [2001:4860:4845:400::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62268  whatsapp-cdn6-shv-03-maa3:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62276  [2603:1046:c04:1422::2]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62277  [2603:1046:c04:1422::2]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62378  hkg07s55-in-f14:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62391  [2001:4860:4845:400::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62392  [64:ff9b::2854:6104]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62398  g2600-14e1-0018-006d-0000-0000-0000-0000:http  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62537  [2403:8600:c090:42:a000::300]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62714  [2620:1ec:33::11]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62773  g2600-140f-5e00-0a82-0000-0000-0000-3114:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:62874  pnmaaa-av-in-x03:https  FIN_WAIT_2
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63034  [64:ff9b::4a97:ee66]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63082  pnmaaa-av-in-x0e:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63101  [64:ff9b::96ab:1b0a]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63187  [64:ff9b::d45:6d82]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63275  pnmaaa-az-in-x03:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63345  lcmaaa-ap-in-x06:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63354  [2001:4860:482b:700::]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63402  [2620:1ec:33:1::11]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63421  [2001:4860:4847:400::]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63434  [2603:1061:14:82::1]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63441  [2603:1061:14:82::1]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63529  fx-in-f136:https       TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63530  lcbomp-in-f95:https    TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:63545  pnmaaa-bf-in-x0e:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:64232  a184-28-109-178:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:64263  ly-in-f94:https        ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:64741  sh-in-f119:https       TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:64750  ec2-34-233-49-149:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:64873  whatsapp-cdn6-shv-03-maa3:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:64874  [64:ff9b::d6b:55d]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:64875  [2603:1046:c04:1017::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:64911  si-in-f188:https       ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:65175  pnmaaa-av-in-x0e:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:65360  [2603:1046:c04:83b::2]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:65440  whatsapp-cdn6-shv-02-maa5:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:65441  [2603:1047:1:88::80]:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:404:c975:9d98]:65442  [64:ff9b::496:df60]:https  TIME_WAIT

3.ARP -a:
C:\Users\acer>arp -a

Interface: 169.254.250.194 --- 0x9
  Internet Address      Physical Address      Type
  169.254.0.245         fc-6d-77-8b-a5-33     dynamic
  169.254.6.251         e0-2e-0b-2a-f2-47     dynamic
  169.254.16.196        ac-45-ef-06-e3-0c     dynamic
  169.254.22.130        c4-0f-08-49-7d-66     dynamic
  169.254.26.96         c8-58-c0-80-06-06     dynamic
  169.254.32.252        fc-6d-77-8b-88-aa     dynamic
  169.254.37.213        54-e4-ed-bb-78-fd     dynamic
  169.254.38.13         28-95-29-61-9c-b6     dynamic
  169.254.40.225        68-34-21-81-84-2c     dynamic
  169.254.47.141        e0-2e-0b-7c-b2-44     dynamic
  169.254.53.108        0c-9a-3c-55-fa-af     dynamic
  169.254.54.127        e0-2e-0b-37-b8-56     dynamic
  169.254.64.75         68-34-21-81-82-fb     dynamic
  169.254.65.208        b8-f7-75-b7-5a-9d     dynamic
  169.254.75.92         fc-6d-77-8b-9d-c2     dynamic
  169.254.78.172        e0-2e-0b-3a-c4-9c     dynamic
  169.254.90.209        fc-6d-77-8b-0d-62     dynamic
  169.254.91.29         7c-b5-66-cd-d6-f1     dynamic
  169.254.91.33         e0-2e-0b-34-31-68     dynamic
  169.254.91.65         cc-5e-f8-67-21-a3     dynamic
  169.254.95.143        b8-f7-75-af-da-7a     dynamic
  169.254.103.41        e0-2e-0b-7a-ca-56     dynamic
  169.254.114.30        e0-2e-0b-2a-0a-cb     dynamic
  169.254.114.59        c0-a8-10-8a-23-43     dynamic
  169.254.117.79        40-c7-3c-23-f2-f3     dynamic
  169.254.119.72        fc-6d-77-6f-f5-1d     dynamic
  169.254.119.214       cc-47-40-75-7e-ae     dynamic
  169.254.120.17        b8-f7-75-b6-e9-af     dynamic
  169.254.128.103       ac-45-ef-06-e3-2a     dynamic
  169.254.133.27        fc-6d-77-9d-24-ed     dynamic
  169.254.136.29        c0-35-32-24-8e-05     dynamic
  169.254.141.99        fc-6d-77-9d-26-28     dynamic
  169.254.148.5         e0-2e-0b-37-e2-ea     dynamic
  169.254.149.59        84-9e-56-ec-ab-b5     dynamic
  169.254.150.143       12-24-9b-55-82-87     dynamic
  169.254.153.127       d4-f3-2d-c7-14-10     dynamic
  169.254.156.11        6c-4b-90-f7-3e-a0     dynamic
  169.254.157.202       40-c7-3c-bb-7a-60     dynamic
  169.254.158.198       b8-f7-75-af-95-a1     dynamic
  169.254.159.249       e0-2e-0b-3b-51-73     dynamic
  169.254.160.71        c0-a8-10-8e-01-a2     dynamic
  169.254.161.210       e0-2e-0b-30-1a-60     dynamic
  169.254.164.166       88-d8-2e-da-0e-26     dynamic
  169.254.165.185       a0-80-69-c0-91-2b     dynamic
  169.254.167.82        fc-6d-77-6f-d2-cc     dynamic
  169.254.172.64        b8-f7-75-b0-47-7b     dynamic
  169.254.177.172       d4-ab-61-c1-99-72     dynamic
  169.254.184.90        44-f7-9f-da-19-a7     dynamic
  169.254.187.176       d4-f3-2d-d8-2d-90     dynamic
  169.254.193.216       fc-6d-77-6f-eb-0e     dynamic
  169.254.193.221       e8-c7-cf-a0-d0-be     dynamic
  169.254.196.202       f0-77-c3-90-62-94     dynamic
  169.254.200.250       c8-5e-a9-44-21-95     dynamic
  169.254.201.178       c4-0f-08-2e-9f-69     dynamic
  169.254.201.246       3c-6a-a7-80-04-6c     dynamic
  169.254.203.18        28-a0-6b-52-4f-3b     dynamic
  169.254.207.40        3c-e9-f7-d4-3f-69     dynamic
  169.254.209.209       9c-c7-d3-12-09-8b     dynamic
  169.254.210.21        14-85-7f-69-74-b3     dynamic
  169.254.214.8         2c-9c-58-70-94-d5     dynamic
  169.254.216.230       fc-6d-77-6c-0f-43     dynamic
  169.254.221.161       c8-15-4e-c4-11-2a     dynamic
  169.254.227.202       24-b2-b9-51-3c-95     dynamic
  169.254.230.6         fc-6d-77-8a-9b-43     dynamic
  169.254.231.142       fc-6d-77-6f-a9-dc     dynamic
  169.254.235.152       ac-50-de-4a-52-dd     dynamic
  169.254.235.215       88-d8-2e-da-00-e3     dynamic
  169.254.235.229       28-2e-89-74-46-8a     dynamic
  169.254.237.235       98-bd-80-d8-fa-27     dynamic
  169.254.245.244       e0-2e-0b-3b-51-78     dynamic
  169.254.247.200       c0-a8-10-8e-0c-6a     dynamic
  169.254.248.114       c4-0f-08-2b-f4-a3     dynamic
  169.254.255.255       ff-ff-ff-ff-ff-ff     static
  224.0.0.2             01-00-5e-00-00-02     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  224.0.2.3             01-00-5e-00-02-03     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static

Interface: 192.168.56.1 --- 0xe
  Internet Address      Physical Address      Type
  192.168.56.255        ff-ff-ff-ff-ff-ff     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  224.0.2.3             01-00-5e-00-02-03     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static

4.HOSTNAME:
C:\Users\acer>hostname
TMP215-75-G2

5.GETMAC:
C:\Users\acer>getmac

Physical Address    Transport Name
=================== ==========================================================
FC-6D-77-8B-5E-29   Media disconnected
FC-6D-77-8B-5E-25   \Device\Tcpip_{5FB3CE5A-5130-4FE2-8121-9315D8FF7313}
74-D4-DD-CF-7D-E7   Media disconnected
0A-00-27-00-00-0E   \Device\Tcpip_{B8F92396-16D1-420E-9B56-EFFA739105B8}

6.ROUTE PRINT:
C:\Users\acer>route print
===========================================================================
Interface List
 14...0a 00 27 00 00 0e ......VirtualBox Host-Only Ethernet Adapter
 12...fc 6d 77 8b 5e 26 ......Microsoft Wi-Fi Direct Virtual Adapter
 21...fe 6d 77 8b 5e 25 ......Microsoft Wi-Fi Direct Virtual Adapter #2
  9...fc 6d 77 8b 5e 25 ......Intel(R) Wi-Fi 6E AX211 160MHz
 18...fc 6d 77 8b 5e 29 ......Bluetooth Device (Personal Area Network)
 16...74 d4 dd cf 7d e7 ......Realtek PCIe GbE Family Controller
  1...........................Software Loopback Interface 1
===========================================================================

IPv4 Route Table
===========================================================================
Active Routes:
Network Destination        Netmask          Gateway       Interface  Metric
        127.0.0.0        255.0.0.0         On-link         127.0.0.1    331
        127.0.0.1  255.255.255.255         On-link         127.0.0.1    331
  127.255.255.255  255.255.255.255         On-link         127.0.0.1    331
      169.254.0.0      255.255.0.0         On-link   169.254.250.194    291
  169.254.250.194  255.255.255.255         On-link   169.254.250.194    291
  169.254.255.255  255.255.255.255         On-link   169.254.250.194    291
     192.168.56.0    255.255.255.0         On-link      192.168.56.1    281
     192.168.56.1  255.255.255.255         On-link      192.168.56.1    281
   192.168.56.255  255.255.255.255         On-link      192.168.56.1    281
        224.0.0.0        240.0.0.0         On-link         127.0.0.1    331
        224.0.0.0        240.0.0.0         On-link      192.168.56.1    281
        224.0.0.0        240.0.0.0         On-link   169.254.250.194    291
  255.255.255.255  255.255.255.255         On-link         127.0.0.1    331
  255.255.255.255  255.255.255.255         On-link      192.168.56.1    281
  255.255.255.255  255.255.255.255         On-link   169.254.250.194    291
===========================================================================
Persistent Routes:
  None

IPv6 Route Table
===========================================================================
Active Routes:
 If Metric Network Destination      Gateway
  9    291 ::/0                     fe80::eedd:24ff:fe3d:ced5
  1    331 ::1/128                  On-link
  9    291 2403:8600:c090:42::/84   On-link
  9    291 2403:8600:c090:42:0:404:c975:9d98/128
                                    On-link
 14    281 fe80::/64                On-link
  9    291 fe80::/64                On-link
  9    291 fe80::504:d8bd:db91:71bd/128
                                    On-link
 14    281 fe80::b246:2d04:ced8:d3ed/128
                                    On-link
  1    331 ff00::/8                 On-link
 14    281 ff00::/8                 On-link
  9    291 ff00::/8                 On-link
===========================================================================
Persistent Routes:
  None

7.NSLOOKUP:
C:\Users\acer>nslookup
Default Server:  UnKnown
Address:  2403:8600:c090:42:a000::200

> lms2.ai.saveetha.in
Server:  UnKnown
Address:  2403:8600:c090:42:a000::200

Name:    lms2.ai.saveetha.in
Address:  2403:8600:c090:42:a000::300


8.ping google.com
C:\Users\acer>ping google.com

Pinging google.com [2404:6800:4007:800::200e] with 32 bytes of data:
Reply from 2404:6800:4007:800::200e: time=7ms
Reply from 2404:6800:4007:800::200e: time=102ms
Reply from 2404:6800:4007:800::200e: time=24ms
Reply from 2404:6800:4007:800::200e: time=27ms

Ping statistics for 2404:6800:4007:800::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 7ms, Maximum = 102ms, Average = 40ms

9.: systeminfo
C:\Users\acer>systeminfo

Host Name:                     TMP215-75-G2
OS Name:                       Microsoft Windows 11 Home Single Language
OS Version:                    10.0.26200 N/A Build 26200
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Standalone Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              acer
Registered Organization:       N/A
Product ID:                    00342-42784-63578-AAOEM
Original Install Date:         01-09-2025, 15:21:05
System Boot Time:              26-10-2026, 09:44:29
System Manufacturer:           Acer
System Model:                  TravelMate P215-75-G2-TCO
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 170 Stepping 4 GenuineIntel ~1200 Mhz
BIOS Version:                  INSYDE Corp. V1.05tt01a, 01-09-2025
Windows Directory:             C:\Windows
System Directory:              C:\Windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  00004009
Time Zone:                     (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi
Total Physical Memory:         15,869 MB
Available Physical Memory:     896 MB
Virtual Memory: Max Size:      27,645 MB
Virtual Memory: Available:     6,715 MB
Virtual Memory: In Use:        20,930 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\TMP215-75-G2
Hotfix(s):                     4 Hotfix(s) Installed.
                               [01]: KB5127690
                               [02]: KB5054156
                               [03]: KB5127648
                               [04]: KB5127647
Network Card(s):               4 NIC(s) Installed.
                               [01]: Bluetooth Device (Personal Area Network)
                                     Connection Name: Bluetooth Network Connection
                                     Status:          Media disconnected
                               [02]: Intel(R) Wi-Fi 6E AX211 160MHz
                                     Connection Name: Wi-Fi
                                     DHCP Enabled:    Yes
                                     DHCP Server:     255.255.255.255
                                     IP address(es)
                                     [01]: 169.254.250.194
                                     [02]: fe80::504:d8bd:db91:71bd
                                     [03]: 2403:8600:c090:42:0:401:c975:9d98
                               [03]: Realtek PCIe GbE Family Controller
                                     Connection Name: Ethernet
                                     Status:          Media disconnected
                               [04]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 2
                                     DHCP Enabled:    No
                                     IP address(es)
                                     [01]: 192.168.56.1
                                     [02]: fe80::b246:2d04:ced8:d3ed
Virtualization-based security: Status: Running
                               Required Security Properties:
                                     Base Virtualization Support
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                                     APIC Virtualization
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Enforced
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

10.Tracert:
C:\Users\acer>tracert google.com

Tracing route to google.com [2404:6800:4007:82e::200e]
over a maximum of 30 hops:

  1    61 ms    77 ms    13 ms  2403:8600:c090:42::1
  2     *        *        *     Request timed out.
  3     *        *        *     Request timed out.
  4     *        *        *     Request timed out.
  5     *        *        *     Request timed out.
  6   160 ms    11 ms    11 ms  pnmaaa-bd-in-x0e.1e100.net [2404:6800:4007:82e::200e]

Trace complete.
```
## Result
Thus Execution of Network commands Performed 
