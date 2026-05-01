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
1.IPCONFIG
```
PS C:\Users\saira> ipconfig

Windows IP Configuration


Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::c0fd:ae4a:5dad:2292%15
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

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2401:4900:1cd0:1187:bc44:44f5:2e6a:ccd4
   Temporary IPv6 Address. . . . . . : 2401:4900:1cd0:1187:a879:e44f:9f95:31a4
   Link-local IPv6 Address . . . . . : fe80::b20c:eb69:f7a:7c5b%6
   IPv4 Address. . . . . . . . . . . : 192.168.1.3
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::1%6
                                       192.168.1.1
```
2.HOSTNAME
```
PS C:\Users\saira> hostname
Sairam
```
3.TRACERT
```
PS C:\Users\saira> tracert

Usage: tracert [-d] [-h maximum_hops] [-j host-list] [-w timeout]
               [-R] [-S srcaddr] [-4] [-6] target_name

Options:
    -d                 Do not resolve addresses to hostnames.
    -h maximum_hops    Maximum number of hops to search for target.
    -j host-list       Loose source route along host-list (IPv4-only).
    -w timeout         Wait timeout milliseconds for each reply.
    -R                 Trace round-trip path (IPv6-only).
    -S srcaddr         Source address to use (IPv6-only).
    -4                 Force using IPv4.
    -6                 Force using IPv6.
```
4.NETSTAT
```
PS C:\Users\saira> netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    127.0.0.1:7768         Sairam:56670           ESTABLISHED
  TCP    127.0.0.1:51162        Sairam:51163           ESTABLISHED
  TCP    127.0.0.1:51163        Sairam:51162           ESTABLISHED
  TCP    127.0.0.1:56670        Sairam:7768            ESTABLISHED
  TCP    127.0.0.1:61993        Sairam:62063           ESTABLISHED
  TCP    127.0.0.1:61993        Sairam:62064           ESTABLISHED
  TCP    127.0.0.1:62063        Sairam:61993           ESTABLISHED
  TCP    127.0.0.1:62064        Sairam:61993           ESTABLISHED
  TCP    192.168.1.3:51164      a23-199-67-18:https    CLOSE_WAIT
  TCP    192.168.1.3:56817      lb-140-82-113-22-iad:https  CLOSE_WAIT
  TCP    192.168.1.3:58707      lb-140-82-113-25-iad:https  ESTABLISHED
  TCP    192.168.1.3:59672      lb-140-82-113-22-iad:https  ESTABLISHED
  TCP    192.168.1.3:60280      202:4070               ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:49784  [2600:1901:1:d18::]:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:50910  [2600:1901:1:7c5::]:https  TIME_WAIT
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:52283  sd-in-f188:5228        ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:52638  g2600-1417-0078-0000-0000-0000-6856-bd31:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:52879  g2600-140f-3a00-0000-0000-0000-17c9-3410:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:53122  [2a04:4e42:25::762]:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:53351  g2600-1417-0020-0000-0000-0000-17cd-7693:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:54215  [2620:1ec:33::10]:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:55169  g2600-1417-0020-018f-0000-0000-0000-3114:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:56793  g2600-1417-0020-0000-0000-0000-17cd-769c:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:56818  [2603:1046:c06:c4e::2]:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:56819  [2603:1046:c06:c4e::2]:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:57676  [2600:1901:0:5e8a::]:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:60285  [2603:1040:a06:6::]:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:60956  g2600-1417-0020-0000-0000-0000-17cd-7693:https  ESTABLISHED
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:62299  [2606:4700:83b3:8af8:99fd:5:3d05:6d0c]:https  CLOSE_WAIT
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:62300  [2606:4700:83b0:bc89:5e3b:891:3fd7:3718]:https  CLOSE_WAIT
  TCP    [2401:4900:1cd0:1187:a879:e44f:9f95:31a4]:64208  [2600:1901:1:d18::]:https  ESTABLISHED
```
5.GETMAC
```
PS C:\Users\saira> getmac

Physical Address    Transport Name
=================== ==========================================================
2C-98-11-56-86-83   \Device\Tcpip_{32BF66F8-F49C-425A-A0B3-B42B9CE9012F}
C4-C6-E6-6F-87-E3   Media disconnected
0A-00-27-00-00-0F   \Device\Tcpip_{A4B5248F-D35D-499C-831C-D11B211D28D9}
```
6.SYSTEMINFO
```
PS C:\Users\saira> systeminfo

Host Name:                     SAIRAM
OS Name:                       Microsoft Windows 11 Home Single Language
OS Version:                    10.0.26200 N/A Build 26200
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Standalone Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              sairam777000@gmail.com
Registered Organization:       N/A
Product ID:                    00342-42694-85205-AAOEM
Original Install Date:         20-05-2025, 01:28:06
System Boot Time:              01-05-2026, 13:14:53
System Manufacturer:           LENOVO
System Model:                  82WM
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: AMD64 Family 25 Model 97 Stepping 2 AuthenticAMD ~2501 Mhz
BIOS Version:                  LENOVO LPCN62WW, 17-06-2025
Windows Directory:             C:\WINDOWS
System Directory:              C:\WINDOWS\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  00004009
Time Zone:                     (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi
Total Physical Memory:         15,553 MB
Available Physical Memory:     4,945 MB
Virtual Memory: Max Size:      30,913 MB
Virtual Memory: Available:     14,201 MB
Virtual Memory: In Use:        16,712 MB
Page File Location(s):         E:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\SAIRAM
Hotfix(s):                     4 Hotfix(s) Installed.
                               [01]: KB5082417
                               [02]: KB5054156
                               [03]: KB5083631
                               [04]: KB5088467
Network Card(s):               3 NIC(s) Installed.
                               [01]: RZ616 Wi-Fi 6E 160MHz
                                     Connection Name: Wi-Fi
                                     DHCP Enabled:    Yes
                                     DHCP Server:     192.168.1.1
                                     IP address(es)
                                     [01]: 192.168.1.3
                                     [02]: fe80::b20c:eb69:f7a:7c5b
                                     [03]: 2401:4900:1cd0:1187:a879:e44f:9f95:31a4
                                     [04]: 2401:4900:1cd0:1187:bc44:44f5:2e6a:ccd4
                               [02]: Realtek PCIe GbE Family Controller
                                     Connection Name: Ethernet
                                     Status:          Media disconnected
                               [03]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 2
                                     DHCP Enabled:    No
                                     IP address(es)
                                     [01]: 192.168.56.1
                                     [02]: fe80::c0fd:ae4a:5dad:2292
Virtualization-based security: Status: Running
                               Required Security Properties:
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.
```
7.TASKLIST
```
PS C:\Users\saira> tasklist

Image Name                     PID Session Name        Session#    Mem Usage
========================= ======== ================ =========== ============
System Idle Process              0 Services                   0          8 K
System                           4 Services                   0      1,232 K
Secure System                  428 Services                   0     69,524 K
Registry                       472 Services                   0     60,320 K
smss.exe                      1132 Services                   0      1,460 K
csrss.exe                     1668 Services                   0      6,444 K
wininit.exe                   1844 Services                   0      8,184 K
csrss.exe                     1852 Console                    1      7,156 K
services.exe                  1932 Services                   0     19,200 K
LsaIso.exe                    1952 Services                   0      4,048 K
lsass.exe                     1960 Services                   0     33,360 K
svchost.exe                   1236 Services                   0     43,932 K
fontdrvhost.exe               1116 Services                   0      3,932 K
svchost.exe                   2060 Services                   0     22,556 K
svchost.exe                   2116 Services                   0     13,808 K
WUDFHost.exe                  2144 Services                   0      7,208 K
WUDFHost.exe                  2196 Services                   0      7,428 K
winlogon.exe                  2264 Console                    1     17,820 K
fontdrvhost.exe               2320 Console                    1      6,812 K
svchost.exe                   2424 Services                   0      6,836 K
svchost.exe                   2460 Services                   0     10,632 K
svchost.exe                   2476 Services                   0     19,916 K
svchost.exe                   2488 Services                   0     17,576 K
dwm.exe                       2676 Console                    1   1,75,972 K
svchost.exe                   2724 Services                   0     12,816 K
svchost.exe                   2760 Services                   0     13,496 K
svchost.exe                   2768 Services                   0     12,836 K
svchost.exe                   2848 Services                   0     21,768 K
svchost.exe                   2956 Services                   0     11,552 K
svchost.exe                   2968 Services                   0     21,844 K
svchost.exe                   2996 Services                   0      7,528 K
svchost.exe                   3016 Services                   0     17,800 K
svchost.exe                   3284 Services                   0      7,624 K
svchost.exe                   3416 Services                   0     12,132 K
svchost.exe                   3484 Services                   0     10,036 K
svchost.exe                   3492 Services                   0     10,988 K
svchost.exe                   3500 Services                   0     14,564 K
svchost.exe                   3696 Services                   0     10,464 K
svchost.exe                   3836 Services                   0      9,864 K
svchost.exe                   3852 Services                   0     13,600 K
NVDisplay.Container.exe       2636 Services                   0     38,800 K
amdfendrsr.exe                4052 Services                   0      9,676 K
atiesrxx.exe                  3924 Services                   0      9,028 K
svchost.exe                   3932 Services                   0     19,480 K
svchost.exe                   4000 Services                   0     27,040 K
svchost.exe                   4184 Services                   0      9,956 K
svchost.exe                   4220 Services                   0     28,760 K
svchost.exe                   4584 Services                   0      8,680 K
NVDisplay.Container.exe       4680 Console                    1     47,676 K
svchost.exe                   4916 Services                   0     11,416 K
svchost.exe                   5028 Services                   0     11,460 K
svchost.exe                   5036 Services                   0     18,556 K
svchost.exe                   5044 Services                   0      7,300 K
atieclxx.exe                  5056 Console                    1     20,428 K
svchost.exe                   4988 Services                   0      8,760 K
svchost.exe                   5124 Services                   0     12,568 K
Memory Compression            5156 Services                   0   7,01,208 K
svchost.exe                   5316 Services                   0     20,124 K
svchost.exe                   5364 Services                   0     10,644 K
svchost.exe                   5608 Services                   0     29,080 K
svchost.exe                   5948 Services                   0      8,364 K
svchost.exe                   5956 Services                   0     13,020 K
svchost.exe                   6104 Services                   0      8,720 K
svchost.exe                   6160 Services                   0     24,480 K
svchost.exe                   6212 Services                   0     28,788 K
svchost.exe                   6220 Services                   0     18,572 K
spoolsv.exe                   6336 Services                   0     19,116 K
svchost.exe                   6444 Services                   0      8,468 K
svchost.exe                   6496 Services                   0     10,072 K
FMService64.exe               6660 Services                   0     12,644 K
svchost.exe                   6668 Services                   0     54,052 K
svchost.exe                   6676 Services                   0     53,200 K
GooglePlayGamesServices.e     6684 Services                   0   1,15,856 K
GameInputRedistService.ex     6696 Services                   0     12,592 K
svchost.exe                   6720 Services                   0     15,088 K
Lenovo.Modern.ImControlle     6732 Services                   0     47,452 K
LenovoVantageService.exe      6740 Services                   0     47,344 K
OfficeClickToRun.exe          6756 Services                   0     53,012 K
nvcontainer.exe               6764 Services                   0     39,208 K
svchost.exe                   6776 Services                   0     10,908 K
LenovoUtilityService.exe      6792 Services                   0     18,764 K
NahimicService.exe            6804 Services                   0     36,904 K
svchost.exe                   6812 Services                   0     25,868 K
SafeExamBrowser.Service.e     6824 Services                   0     27,904 K
UDClientService.exe           6840 Services                   0     56,800 K
svchost.exe                   6856 Services                   0      7,068 K
MsMpEng.exe                   6864 Services                   0   3,35,948 K
MpDefenderCoreService.exe     6872 Services                   0     27,252 K
Tobii.Service.exe             6896 Services                   0     29,340 K
RtkAudUService64.exe          6888 Services                   0     16,988 K
GameInputRedistService.ex     6424 Console                    1     14,300 K
WmiPrvSE.exe                  7792 Services                   0     39,152 K
crashpad_handler.exe          9148 Services                   0      6,380 K
svchost.exe                   9136 Services                   0     25,852 K
svchost.exe                   9760 Services                   0      9,328 K
gamingservices.exe            9676 Services                   0     44,592 K
gamingservicesnet.exe         9820 Services                   0     11,812 K
SearchIndexer.exe            10144 Services                   0     33,584 K
sihost.exe                    6552 Console                    1     50,028 K
svchost.exe                   9856 Console                    1     10,896 K
svchost.exe                   2664 Console                    1     34,680 K
wlanext.exe                  10276 Services                   0      7,176 K
svchost.exe                  10320 Console                    1     10,596 K
svchost.exe                  10420 Console                    1     51,632 K
taskhostw.exe                10520 Console                    1     19,808 K
svchost.exe                  10740 Services                   0     27,016 K
svchost.exe                  10788 Services                   0     15,664 K
AggregatorHost.exe           11112 Services                   0     11,672 K
svchost.exe                  10700 Services                   0     25,884 K
explorer.exe                 11272 Console                    1   3,28,236 K
CrossDeviceResume.exe        11752 Console                    1     58,208 K
NahimicSvc64.exe             11996 Console                    1      9,208 K
NahimicSvc32.exe             12004 Console                    1      4,008 K
svchost.exe                  11576 Services                   0     11,316 K
svchost.exe                  12776 Services                   0     37,976 K
svchost.exe                  12796 Services                   0     11,244 K
svchost.exe                  12904 Services                   0     14,340 K
NgcIso.exe                   12932 Services                   0      5,104 K
svchost.exe                  13140 Console                    1     28,184 K
svchost.exe                  13212 Services                   0      5,680 K
nvcontainer.exe              12672 Console                    1     42,572 K
nvcontainer.exe              10392 Console                    1     70,496 K
svchost.exe                  13380 Services                   0     32,040 K
svchost.exe                  13660 Services                   0     20,596 K
Widgets.exe                  13728 Console                    1     67,080 K
WidgetService.exe            14740 Console                    1     28,664 K
SearchHost.exe               14812 Console                    1   1,42,184 K
StartMenuExperienceHost.e    14820 Console                    1   1,72,616 K
svchost.exe                  15004 Services                   0     29,972 K
svchost.exe                  15156 Services                   0     10,000 K
RuntimeBroker.exe            15372 Console                    1     63,076 K
svchost.exe                  15424 Services                   0     21,128 K
svchost.exe                  15436 Console                    1     23,704 K
ShellExperienceHost.exe      16508 Console                    1     81,848 K
ctfmon.exe                   17144 Console                    1     31,664 K
msedgewebview2.exe           17236 Console                    1   1,24,092 K
msedgewebview2.exe           16736 Console                    1     11,768 K
LockApp.exe                  17244 Console                    1     84,488 K
msedgewebview2.exe           17452 Console                    1     44,248 K
msedgewebview2.exe           16624 Console                    1   1,20,664 K
msedgewebview2.exe           18292 Console                    1     21,836 K
NisSrv.exe                   18924 Services                   0     14,164 K
RuntimeBroker.exe            19000 Console                    1     47,924 K
msedgewebview2.exe           19308 Console                    1   1,24,184 K
svchost.exe                  19288 Services                   0     16,868 K
svchost.exe                  19496 Console                    1     22,280 K
CrossDeviceService.exe       19644 Console                    1   1,04,920 K
LenovoVantage-(VantageCor    20932 Services                   0     10,100 K
FnHotkeyCapsLKNumLK.exe      20968 Console                    1     16,128 K
FnHotkeyUtility.exe          20840 Console                    1     44,572 K
unsecapp.exe                 21096 Console                    1      9,664 K
RuntimeBroker.exe            21876 Console                    1     13,268 K
LenovoVantage-(LenovoGami    21912 Services                   0     10,772 K
unsecapp.exe                 20544 Console                    1     10,324 K
unsecapp.exe                 15652 Services                   0     11,592 K
PhoneExperienceHost.exe      14524 Console                    1   1,62,392 K
SecurityHealthSystray.exe    22728 Console                    1     13,340 K
SecurityHealthService.exe    22800 Services                   0     23,340 K
TextInputHost.exe            23112 Console                    1   1,28,188 K
RtkAudUService64.exe         23264 Console                    1     21,016 K
svchost.exe                  23948 Services                   0     14,636 K
RadeonSoftware.exe           24092 Console                    1     28,212 K
AppleMobileDeviceLauncher    24364 Console                    1     11,676 K
SpotifyLauncher.exe          24544 Console                    1     45,388 K
cncmd.exe                    23612 Console                    1      7,664 K
crashpad_handler.exe         23644 Console                    1      9,716 K
AMDRSServ.exe                23904 Console                    1     27,652 K
amdow.exe                    24348 Console                    1      2,764 K
AMDRSSrcExt.exe              24196 Console                    1     55,224 K
AppleMobileDeviceProcess.    25072 Console                    1     16,096 K
nahimicNotifSys.exe           9368 Console                    1     51,120 K
ApplicationFrameHost.exe     25440 Console                    1     46,624 K
Nahimic3.exe                 21572 Console                    1     71,216 K
RuntimeBroker.exe             3444 Console                    1     24,908 K
svchost.exe                  24616 Services                   0     15,312 K
msedgewebview2.exe           20052 Console                    1     20,432 K
msedgewebview2.exe           11708 Console                    1     14,412 K
msedgewebview2.exe            3044 Console                    1      7,504 K
msedgewebview2.exe            6112 Console                    1      9,780 K
msedgewebview2.exe           20320 Console                    1         48 K
msedgewebview2.exe            6244 Console                    1      1,088 K
MessagingPlugin.exe          15784 Console                    1     43,308 K
conhost.exe                  12712 Console                    1      6,996 K
AppProvisioningPlugin.exe     6256 Services                   0     32,036 K
conhost.exe                  19724 Services                   0     10,328 K
RuntimeBroker.exe            26456 Console                    1     36,112 K
svchost.exe                  17024 Console                    1     26,236 K
svchost.exe                  16516 Services                   0      9,672 K
svchost.exe                  16464 Services                   0     32,548 K
svchost.exe                  16956 Services                   0     12,840 K
Locator.exe                  15016 Services                   0      3,856 K
LenovoVantage-(GenericMes    16068 Console                    1      5,332 K
backgroundTaskHost.exe       22512 Console                    1      4,948 K
RuntimeBroker.exe            14996 Console                    1     11,748 K
LenovoVantage-(LenovoServ    17436 Console                    1      6,668 K
SystemSettings.exe            5768 Console                    1      2,616 K
svchost.exe                  16224 Services                   0      9,196 K
svchost.exe                  19384 Console                    1     14,436 K
UserOOBEBroker.exe           24612 Console                    1     11,476 K
svchost.exe                  10992 Services                   0     13,316 K
svchost.exe                  11068 Services                   0     16,536 K
AppActions.exe               16460 Console                    1     43,700 K
svchost.exe                  14592 Services                   0     13,056 K
SDXHelper.exe                 6960 Console                    1     32,688 K
MoNotificationUx.exe         17828 Console                    1     14,920 K
svchost.exe                  27760 Services                   0      9,504 K
XboxPcAppFT.exe              28576 Console                    1     51,852 K
svchost.exe                  28892 Services                   0     17,416 K
backgroundTaskHost.exe       11308 Console                    1     56,548 K
RuntimeBroker.exe            10924 Console                    1     28,760 K
taskhostw.exe                33464 Console                    1     24,132 K
FMAudioMonitor.exe           21620 Console                    1     10,868 K
chrome.exe                    9684 Console                    1   2,66,084 K
chrome.exe                   29472 Console                    1     11,908 K
chrome.exe                   29092 Console                    1   6,49,660 K
chrome.exe                   14340 Console                    1     61,628 K
chrome.exe                    6316 Console                    1     19,660 K
chrome.exe                   28644 Console                    1     59,292 K
chrome.exe                   35644 Console                    1     52,184 K
chrome.exe                   18936 Console                    1     23,160 K
backgroundTaskHost.exe       12460 Console                    1     17,524 K
RuntimeBroker.exe            30912 Console                    1     14,660 K
chrome.exe                   26136 Console                    1   1,05,040 K
RuntimeBroker.exe            32380 Console                    1     15,404 K
Spotify.exe                   9916 Console                    1   2,48,416 K
Spotify.exe                  36968 Console                    1     11,180 K
Spotify.exe                  37852 Console                    1   2,92,456 K
Spotify.exe                  28620 Console                    1     51,220 K
Spotify.exe                  35624 Console                    1     23,656 K
Spotify.exe                  36888 Console                    1   2,78,632 K
Spotify.exe                  27396 Console                    1     33,124 K
chrome.exe                   14852 Console                    1   1,49,208 K
RuntimeBroker.exe            14872 Console                    1     13,800 K
chrome.exe                   33400 Console                    1     41,656 K
WhatsApp.Root.exe            30316 Console                    1   1,46,456 K
backgroundTaskHost.exe       34644 Console                    1      1,948 K
svchost.exe                  24764 Services                   0     24,648 K
svchost.exe                  37388 Services                   0     27,504 K
chrome.exe                   26540 Console                    1     26,332 K
chrome.exe                   23016 Console                    1   1,69,324 K
ShellHost.exe                39868 Console                    1     50,900 K
WmiApSrv.exe                 29024 Services                   0     12,368 K
platform_runtime_RGB_serv    42408 Services                   0   2,28,320 K
chrome.exe                   42076 Console                    1   1,75,040 K
platform_runtime_RGB_serv    42152 Services                   0   2,28,400 K
svchost.exe                  42064 Services                   0      7,784 K
audiodg.exe                  42940 Services                   0     27,724 K
Lenovo.Modern.ImControlle    39364 Console                    1     38,728 K
WindowsTerminal.exe          32964 Console                    1   1,28,520 K
OpenConsole.exe              43564 Console                    1     12,908 K
powershell.exe               40472 Console                    1     76,180 K
WmiPrvSE.exe                 40668 Services                   0     24,380 K
WmiPrvSE.exe                 43828 Services                   0     13,484 K
TrustedInstaller.exe         39636 Services                   0     10,060 K
TiWorker.exe                 36736 Services                   0     18,280 K
tasklist.exe                 35892 Console                    1     11,796 K
```
8.WHOAMI
``` 
PS C:\Users\saira> whoami
sairam\saira
```
9.PING
```
PS C:\Users\saira> ping google.com

Pinging google.com [2404:6800:4007:83a::200e] with 32 bytes of data:
Reply from 2404:6800:4007:83a::200e: time=6ms
Reply from 2404:6800:4007:83a::200e: time=5ms
Reply from 2404:6800:4007:83a::200e: time=6ms
Reply from 2404:6800:4007:83a::200e: time=5ms

Ping statistics for 2404:6800:4007:83a::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 5ms, Maximum = 6ms, Average = 5ms
```
10.NSLOOKUP
```
PS C:\Users\saira> nslookup
DNS request timed out.
    timeout was 2 seconds.
Default Server:  UnKnown
Address:  fe80::1

```

## Result
Thus Execution of Network commands Performed 
