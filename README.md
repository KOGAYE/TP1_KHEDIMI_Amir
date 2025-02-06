# TP1 : Plip plap votre OS

# I. Ressources de l'OS

## 1. Programme, service, processus

Liste tous les processus en cours sur ma machine

```bash
PS C:\Users\kogay> get-process

Handles  NPM(K)    PM(K)      WS(K)     CPU(s)     Id  SI ProcessName
-------  ------    -----      -----     ------     --  -- -----------
     91       7     1320       2056              5264   0 AAADSvc
   1127      51    78144      18220     144,47  22960   3 ACCStd
    123       9     3820       2096              5244   0 ACCSvc
    236      12     2700       6076       3,22  14564   3 ACCUserPS
    260      16     9072      11348             10380   0 AcerCCAgent
    271      17     9272      12012              5292   0 AcerDIAgent
    363      20    22556      11148              5436   0 AcerEZService
    335      15     4776       3144              5308   0 AcerPixyService
    501      24    11092      23712              5324   0 AcerQAAgent
    614      31   162920     166680     698,86   9084   3 AcerSense
    925      69    90088      76104     262,05  12932   3 AcerSense
    326      21    14324      47516      41,39  13008   3 AcerSense
    339      29    23000      10088     172,00  15168   3 AcerSense
    329      58    34572       7596              6448   0 AcerService
    258      15    19112       3356              5316   0 AcerServiceWrapper
    249      16     4160       3944              2992   3 AcerSysHardwareService
    321      20     9388       2696             20984   0 AcerSysMonitorService
 191857       7     3304       4196              4652   0 AcerSystemCentralService
    151       9     1672       4368             18600   0 ADESv2BW
    744      18     1788       2688              5300   0 ADESv2Svc
    232      14     7856       8068              8440   0 AggregatorHost
    152      10     2608       2352              2964   0 amdfendrsr
    167      11     2264       2064       0,88   1380   3 amdow
   1014      34    55716      12940      56,53  14232   3 AMDRSServ
    413      39   122164       7544      31,25  21088   3 AMDRSSrcExt
    394      24    16152       8724       0,86  13432   3 ApplicationFrameHost
    325      24     7696       8880      29,33   8556   3 AQAUserPS
    124       9     1740       2620              5272   0 ARTAimmxService
    346      17     4704       7548             22492   3 atieclxx
    214      10     2500       2224              2972   0 atiesrxx
    326      14    32784      39244     543,25   9960   0 audiodg
    338      28    17892        916       0,30  32648   3 backgroundTaskHost
    260      16     7708      13440       2,75  15908   3 chrome
    448      37   131176     169092     118,03  19648   3 chrome
   1170      50   355328     246952     396,39  20484   3 chrome
    595      28    14816      16024       1,66  22288   3 chrome
   2306      69   168008     257392     625,14  24104   3 chrome
    327      25    61516      76012      48,00  28172   3 chrome
    268      24    22468      18724       1,67  28476   3 chrome
    208      13    13632      12124       4,86  28764   3 chrome
    406      35   111308     123140      13,58  30140   3 chrome
    459     210    28588      47492     101,52  31336   3 chrome
    204      10     2236       4324       0,23  31372   3 chrome
    372      29    75180     133648       3,36  34948   3 chrome
    175      13     7180      18744       0,11  35340   3 chrome
    228      20    15640      33132       0,13  38348   3 chrome
    133      10     1648       1372       0,03  12308   3 cncmd
    140      10     1600       1880              3436   0 conhost
    140      10     1596       1860              6392   0 conhost
    142      10     1584       1876              6444   0 conhost
    140      10     1592       1864              6740   0 conhost
    140      10     1592       1864              6916   0 conhost
    140      10     1588       1868              7128   0 conhost
    141      10     1644       1808              7468   0 conhost
    140      10     1604       1884              7612   0 conhost
    143       9     1536      10220       0,02  35184   3 conhost
     90       8     1208       7364             35892   0 crashpad_handler
    684      79    18696      29088      18,50  12232   3 CrossDeviceService
    898      30     2348       3100              1052   0 csrss
    866      27     6212       6436             12564   3 csrss
    633      22    11004      19608     171,77  17848   3 ctfmon
    362      18     4836       9712              3100   0 dasHost
   1428     116   487264     308320   2 319,19   8176   3 Discord
    278      16    12268       3792       3,97   8308   3 Discord
   1451      61   145988      50564     223,11  11888   3 Discord
    195      13    11356       2484       0,31  12360   3 Discord
    807      40   369316     104708     264,20  15832   3 Discord
    358      21    17516      18636      37,58  20540   3 Discord
    147      10     2316       4980      11,02  13940   3 dllhost
    124       9     1664       2476       0,06  16600   3 dllhost
    705      67    19556      26220       3,19  17368   3 dllhost
   1881      70   169588      99540              8580   3 dwm
   6182     162   323216     386140   1 721,28  21024   3 explorer
    220      16    10792      12888      51,23  20856   3 FileCoAuth
    452      18     6684      13832             19076   0 FileSyncHelper
    521      25    11040      15416      43,69  19548   3 flux
     42       7     2292        956              1532   0 fontdrvhost
     42      10     5316       3312             24556   3 fontdrvhost
    464      33    18848       6484              5380   0 GameManagerService
    853      26    10912      24904              7020   0 gamingservices
    140       7     1248       1168              7108   0 gamingservicesnet
    606      41    47736      67772             40232   0 GooglePlayGamesServices
    322      17     6048       5960       2,06   3248   3 HostAppServiceUpdater
      0       0       60          8                 0   0 Idle
    415      20     3752       4528       1,27   2800   3 jucheck
    456      22     3916       6592       0,67  23636   3 jusched
    606      30    19532      58720       1,41  30484   3 LockApp
     63      18     2104       1792              1360   0 LsaIso
   2049      27    13220      19516              1368   0 lsass
      0       0     2768     326736              2096   0 Memory Compression
    559      31    44212      24172       5,98  16876   3 Microsoft.SharePoint
    591      24     9576      29336       9,95   7244   3 MicrosoftStartFeedProvider
    511      18    16404      13156              5488   0 MpDefenderCoreService
    161       9     2240       2496       0,20   3848   3 msedgewebview2
   1051      37   194884     139360     162,50   5880   3 msedgewebview2
   1478      50    46596      62776      23,64  11808   3 msedgewebview2
    218      13     7464       5844       1,95  13740   3 msedgewebview2
    177      10     9292       8132       1,02  19280   3 msedgewebview2
    371      18    13436      23768      10,94  19564   3 msedgewebview2
    241      19    17744       8112       0,50  23020   3 msedgewebview2
    787      80   232748     226288     295,47  24336   3 msedgewebview2
   1088     233   364880     295756              5416   0 MsMpEng
    212      11     4228       5436             10020   0 NisSrv
    635      35    34820      94016       3,52  38132   3 Notepad
    895      28    48072      30308              5564   0 OfficeClickToRun
   1162      68    88268      85056     425,92  25012   3 OneDrive
    296      16     3476      21040       0,44  30828   3 OpenConsole
   1535     105    58280      93264       8,94  30144   3 PhoneExperienceHost
    680      32    56144      76740       2,34  24636   3 powershell
   1392      74   232124      36376     124,58   5136   3 RadeonSoftware
   2199     249    84292      31980              8616   0 Razer Synapse Service
   1094      62    44456      37048     195,88  16572   3 Razer Synapse Service Process
    861      45    31220      26328              5340   0 RazerCentralService
      0      22    13236      56640               280   0 Registry
    507      16     5828       6028              5472   0 RtkAudUService64
    438      15     4396       7520       5,91   9024   3 RtkAudUService64
    405      14     3568       4788             19284   3 RtkAudUService64
    152      10     2356       2920       0,31   8804   3 RuntimeBroker
    954      40    16628      44220      16,78  14484   3 RuntimeBroker
    357      20     6716      16044       1,94  14816   3 RuntimeBroker
    170      11     2796      15276       0,05  17620   3 RuntimeBroker
    137       9     2056       2244       0,23  21156   3 RuntimeBroker
    160      10     2452       2988       0,34  22612   3 RuntimeBroker
    444      24    10316      35936       6,91  23072   3 RuntimeBroker
    582      26    12400      36796       4,86  33160   3 RuntimeBroker
    220      22     4808       3224              6324   0 RzAppManager
    214      11     2896       1768              6356   0 RzBTLEManager
    118      12     1496       1296              9272   0 RzChromaConnectServer
    172      14     2096       2016             10668   0 RzChromaStreamServer
    157      11     1540       1808              6816   0 RzDeviceManager
    161      13     1756       1508              6892   0 RzDiagnostic
    101       9     1224       1252              7088   0 RzIoTDeviceManager
    211      17     2880       2224              5424   0 RzSDKServer
    152      14     2212       2388              5372   0 RzSDKService
    101       9     1216       1260              7148   0 RzSmartlightingDeviceManager
    181      10     2252      11804             38560   0 SearchFilterHost
   1816     200   284608     365988      89,77  21060   3 SearchHost
    929      29    37332      45440             10044   0 SearchIndexer
    412      14     3576      20180             32408   0 SearchProtocolHost
      0       0      172      64868               236   0 Secure System
    486      20     7872      10200             13792   0 SecurityHealthService
    176      10     2052       3776       0,09  13000   3 SecurityHealthSystray
    780      40    32704      31856              1456   0 servicehost
    943      17     7316       9360              1304   0 services
    824      38    28576      32928       5,50  11332   3 ShellExperienceHost
    411      23    14184      46668       0,30  24724   3 ShellHost
    795      23     8604      27196      69,56   5024   3 sihost
    183      11     2760      12988       0,09  34788   3 smartscreen
     58       4     1140        652               796   0 smss
    569      30     8808       7668              4848   0 spoolsv
   1031      48    72424      97432      20,19  15732   3 StartMenuExperienceHost
   1115      22     8632      16828              1204   0 svchost
    327      16     4084       8740              1280   0 svchost
   1738      28    23460      38020              1500   0 svchost
   1610      22    13392      19032              1620   0 svchost
    364      15     3276       5028              1676   0 svchost
    105      12     1360       1416              1780   0 svchost
    169      38     8416       8992              1824   0 svchost
    257      13     3140       6240              1916   0 svchost
    355      10     2324       5576              1924   0 svchost
    490      16     4744       6888              1976   0 svchost
    338      11     2988       5652              2008   0 svchost
    256      11     2796       4976              2036   0 svchost
    145      10     2084       2324              2080   0 svchost
    205      10     2244       4728              2232   0 svchost
    507      14     3164       7816              2368   0 svchost
    364      16     7972      22376              2540   0 svchost
    337      29     3828      10924              2576   0 svchost
    309      12     3656       5416              2656   0 svchost
    383      16     6748      10784              2688   0 svchost
    199      10     2588       5748              2832   0 svchost
    291      12     3564       7628              2892   0 svchost
    497      13    19020      16248              2980   0 svchost
    598      18     8424      21700      20,06   3048   3 svchost
    239       7     2192       2844              3276   0 svchost
    125       8     1840       4076              3368   0 svchost
    210      12     2484       6488              3472   0 svchost
    201      10     2116       2504              3504   0 svchost
    547      16    18764      22140              3528   0 svchost
    179       9     2020       4872              3576   0 svchost
    286      11     2468       4196              3596   0 svchost
    275       8     1424       1648              3796   0 svchost
    182      13     2004       6192              3800   0 svchost
    251      14     3808       7792              3824   0 svchost
    117       8     1572       2116              3952   0 svchost
    245      31     2248       3168              4004   0 svchost
    295      33     3556       6964              4012   0 svchost
    209      10     2260       3576              4076   0 svchost
    591      14     4356       9612              4172   0 svchost
    161       9     1592       3356              4208   0 svchost
    351      10    18904      20192              4336   0 svchost
    216      11     2316       4108              4436   0 svchost
    406      16     4424       7648              4464   0 svchost
    130       9     1764       1948              4540   0 svchost
    530      34    16788      27736              4592   0 svchost
    613      28    10808      16084              4684   0 svchost
    355      16     3752       9908              4712   0 svchost
    137       9     1472       1416              4756   0 svchost
    520      19     7452      17540              4856   0 svchost
    179      10     1876       3052              5048   0 svchost
    418      27     4844      12048              5348   0 svchost
    474      20     5260      18720              5364   0 svchost
    381      21     3012       7220              5388   0 svchost
    432      20    21188      27948              5396   0 svchost
    131       7     1632       2016              5408   0 svchost
    803      31    28120      31344              5496   0 svchost
    613      34    12864      19160              6508   0 svchost
    272      13     3516       9568              7040   0 svchost
    215      12     2464       4232              7452   0 svchost
    115       8     2088       3472              8560   0 svchost
     88       6     1072       1592              8632   0 svchost
    196      10     2764       5996              9136   0 svchost
    306      21     3064       4980              9200   0 svchost
    524      22     9336      13440              9208   0 svchost
    264      12     2800       5316              9288   0 svchost
    511      25     6992      17684              9520   0 svchost
    264      13    12892      12364              9748   0 svchost
    151      10     2340       4580       1,06  10080   3 svchost
    401      18    10272      17444             10128   0 svchost
    256      14     3628       5336             10832   0 svchost
    760      18     6488      14628             11048   0 svchost
   2086      12     2740       8404             11776   0 svchost
    148       9     2000       4524       0,16  15472   3 svchost
    360      17     4708      16532       4,03  16532   3 svchost
    423      24     5672       7564       1,27  17092   3 svchost
    288      15     4116       8780       0,97  17324   3 svchost
    166      10     2028       2248             17448   0 svchost
    340      16     4576      15272             18008   0 svchost
    473      18     4732      17036             18356   0 svchost
    537      19     9200      26780      10,89  18360   3 svchost
    300      14     3000       8136             18500   0 svchost
    155      42     1816       1612             19544   0 svchost
    455      24     3768       6580             19656   0 svchost
    137       9     2080       2236       0,16  21092   3 svchost
    341      15     4268      10988       2,17  23240   3 svchost
    162      13     8444      16656             32020   0 svchost
    193      15     7316       6088             32592   0 svchost
    259      16     4100      17556             34344   0 svchost
   6754       0       40        136                 4   0 System
   1365      72    71104       1348       2,25   8872   3 SystemSettings
    327      49    13204      14180       6,73  13788   3 taskhostw
    710      29    13600      38588       3,16  21812   3 taskhostw
   1012      37    23492      37228      79,72   7760   3 TextInputHost
    504      27    18160      21456     123,41   1224   3 TranslucentTB
    537      31    20796      20592     159,52  10356   3 uihost
    136      10     1844       3364             10004   0 unsecapp
    548      16    12436      29400       2,34  24200   3 VBoxNetDHCP
     83       5     1980       5736       0,34  25996   3 VBoxNetDHCP
     76       5     1196       9284       0,27  34752   3 VBoxNetDHCP
    215      11     2396      14272             25384   0 VBoxSDS
   2295      17     6116      23780       1,00  34472   3 VBoxSVC
    175      10     1784       2228      29,98   6880   3 vgtray
    635      30    80648     121388       4,28  38608   3 VirtualBox
   1301      48  2236672     944680      70,59  12980   3 VirtualBoxVM
     77       5     2172       9260       0,27  15576   3 VirtualBoxVM
     84       5     2996       5700       0,33  37192   3 VirtualBoxVM
    520      41    44788      50992     843,11  23128   3 wallpaper32
    887      40    39180      57248      21,84  13192   3 WidgetBoard
    339      19     5532       9228       3,64  14592   3 WidgetService
    677      35    29128      87304       1,81  11088   3 WindowsTerminal
    166      11     1696       1352              1192   0 wininit
    296      14     2868       6472             12224   3 winlogon
    119       8     1324       1788              4204   0 wlanext
    177      14     2180      12392             36220   0 WmiApSrv
    430      26    53288      54356              9732   0 WmiPrvSE
    238      15     9816      21924             34412   0 WmiPrvSE
    425      19     5660      10952       0,73  31784   3 XboxPcAppFT
```

Liste les 3 processus qui ont le plus petit identifiant

````bash
PS C:\Users\kogay> Get-Process | Sort-Object Id | Select-Object -First 3

Handles  NPM(K)    PM(K)      WS(K)     CPU(s)     Id  SI ProcessName
-------  ------    -----      -----     ------     --  -- -----------
      0       0       60          8                 0   0 Idle
   6497       0       40        136                 4   0 System
      0       0      172      64868               236   0 Secure System
````



Liste tous les services de la machine( en cours d'éxecution)

````bash
PS C:\Users\kogay> Get-Service | Where-Object { $_.Status -eq 'Running' }

Status   Name               DisplayName
------   ----               -----------
Running  ACCSvc             ACC Service
Running  AcerARTAIMMXDri... AAADSvc
Running  AcerARTAIMMXSer... ARTAimmxService
Running  AcerCCAgentSvis    Acer Care Center
Running  AcerDeviceEnabl... Acer Device Enabling Sevice V2
Running  AcerDIAgentSvis    Acer Device Info
Running  AcerEZSvc          Acer Experience Zone Component Service
Running  AcerPixyService    AcerPixyService
Running  AcerQAAgentSvis    Acer Quick Access
Running  AcerServiceSvc     Acer Service Component Service
Running  AMD Crash Defen... AMD Crash Defender Service
Running  AMD External Ev... AMD External Events Utility
Running  Appinfo            Informations d’application
Running  AppXSvc            Service de déploiement AppX (AppXSVC)
Running  ASMSvc             Acer System Monitor Service
Running  AudioEndpointBu... Générateur de points de terminaison...
Running  Audiosrv           Audio Windows
Running  BFE                Moteur de filtrage de base
Running  BITS               Service de transfert intelligent en...
Running  BluetoothUserSe... Service de support des utilisateurs...
Running  BrokerInfrastru... Service d’infrastructure des tâches...
Running  BTAGService        Service de passerelle audio Bluetooth
Running  BthAvctpSvc        Service AVCTP
Running  bthserv            Service de prise en charge Bluetooth
Running  camsvc             Service Gestionnaire d’accès aux fo...
Running  cbdhsvc_3264532    Service utilisateur du Presse-papie...
Running  CDPSvc             Service de plateforme des appareils...
Running  CDPUserSvc_3264532 Service pour utilisateur de platefo...
Running  ClickToRunSvc      Microsoft Office Click-to-Run Service
Running  CoreMessagingRe... CoreMessaging
Running  CryptSvc           Services de chiffrement
Running  DcomLaunch         Lanceur de processus serveur DCOM
Running  DeviceAssociati... Service d’association de périphérique
Running  DeviceInstall      Service d’installation de périphérique
Running  DevicesFlowUser... Flux d’appareils_3264532
Running  DevQueryBroker     Service Broker de découverte en arr...
Running  Dhcp               Client DHCP
Running  DiagTrack          Expériences des utilisateurs connec...
Running  DispBrokerDeskt... Service de stratégie d'affichage
Running  DisplayEnhancem... Service d'amélioration de l'affichage
Running  Dnscache           Client DNS
Running  DoSvc              Optimisation de livraison
Running  DPS                Service de stratégie de diagnostic
Running  DsSvc              Service de partage des données
Running  DusmSvc            Consommation des données
Running  EapHost            Protocole EAP (Extensible Authentic...
Running  EventLog           Journal d’événements Windows
Running  EventSystem        Système d’événement COM+
Running  FileSyncHelper     FileSyncHelper
Running  FontCache          Service de cache de police Windows
Running  GamingServices     Gaming Services
Running  GamingServicesNet  Gaming Services
Running  GooglePlayGames... Google Play Games Services (25.1.86...
Running  gpsvc              Client de stratégie de groupe
Running  hidserv            Service du périphérique d’interface...
Running  hns                Service de réseau hôte
Running  HvHost             Service d'hôte HV
Running  InstallService     Installation du service Microsoft S...
Running  iphlpsvc           Assistance IP
Running  KeyIso             Isolation de clé CNG
Running  LanmanServer       Serveur
Running  LanmanWorkstation  Station de travail
Running  lfsvc              Service de géolocalisation
Running  LicenseManager     Serveur Gestionnaire de licences Wi...
Running  LSM                Gestionnaire de session locale
Running  McAfee WebAdvisor  McAfee WebAdvisor
Running  MDCoreSvc          Microsoft Defender Service de base
Running  mpssvc             Pare-feu Windows Defender
Running  NcbService         Service Broker pour les connexions ...
Running  netprofm           Service Liste des réseaux
Running  NPSMSvc_3264532    Lecture en cours du service du Resp...
Running  nsi                Service Interface du magasin réseau
Running  nvagent            Service de virtualisation de réseau
Running  OneSyncSvc_3264532 Hôte de synchronisation_3264532
Running  PcaSvc             Service de l’Assistant Compatibilit...
Running  PhoneSvc           Service téléphonique
Running  PimIndexMainten... Données de contacts_3264532
Running  PlugPlay           Plug-and-Play
Running  Power              Alimentation
Running  ProfSvc            Service de profil utilisateur
Running  RasMan             Gestionnaire des connexions d’accès...
Running  Razer Chroma SD... Razer Chroma SDK Server
Running  Razer Chroma SD... Razer Chroma SDK Service
Running  Razer Chroma St... Razer Chroma Stream Server
Running  Razer Game Mana... Razer Game Manager
Running  Razer Synapse S... Razer Synapse Service
Running  RmSvc              Service de gestion radio
Running  RpcEptMapper       Mappeur de point de terminaison RPC
Running  RpcSs              Appel de procédure distante (RPC)
Running  RtkAudioUnivers... Realtek Audio Universal Service
Running  RzActionSvc        Razer Central Service
Running  SamSs              Gestionnaire de comptes de sécurité
Running  Schedule           Planificateur de tâches
Running  SecurityHealthS... Service Sécurité Windows
Running  SENS               Service de notification d’événement...
Running  SensorService      Service de capteur
Running  SharedAccess       Partage de connexion Internet (ICS)
Running  ShellHWDetection   Détection matériel noyau
Running  Spooler            Spouleur d’impression
Running  SSDPSRV            Découverte SSDP
Running  SstpSvc            Service SSTP (Secure Socket Tunneli...
Running  StateRepository    Service State Repository (StateRepo...
Running  StiSvc             Acquisition d’image Windows (WIA)
Running  StorSvc            Service de stockage
Running  SysMain            SysMain
Running  SystemEventsBroker Service Broker des événements système
Running  TextInputManage... Service de gestion des entrées de t...
Running  Themes             Thèmes
Running  TimeBrokerSvc      Service Broker pour les événements ...
Running  TokenBroker        Gestionnaire de comptes web
Running  TrkWks             Client de suivi de lien distribué
Running  UdkUserSvc_3264532 Service utilisateur du kit de dével...
Running  UnistoreSvc_326... Stockage des données utilisateur_32...
Running  UserDataSvc_326... Accès aux données utilisateur_3264532
Running  UserManager        Gestionnaire des utilisateurs
Running  UsoSvc             Service Orchestrator pour les mises...
Running  VaultSvc           Gestionnaire d’informations d’ident...
Running  VBoxSDS            VirtualBox system service
Running  Wcmsvc             Gestionnaire des connexions Windows
Running  WdiSystemHost      Hôte système de diagnostics
Running  WdNisSvc           Service d’inspection réseau de l’an...
Running  webthreatdefsvc    Service Web Threat Defense
Running  webthreatdefuse... Service d’utilisateur Web Threat De...
Running  WinDefend          Service antivirus Microsoft Defender
Running  WinHttpAutoProx... Service de découverte automatique d...
Running  Winmgmt            Infrastructure de gestion Windows
Running  WlanSvc            Service de configuration automatiqu...
Running  wmiApSrv           Carte de performance WMI
Running  WpnService         Service du système de notifications...
Running  WpnUserService_... Service utilisateur de notification...
Running  wscsvc             Centre de sécurité
Running  WSearch            Windows Search
Running  XblAuthManager     Gestionnaire d'authentification Xbo...
````


Liste tous les services de la machine(ceux pas en lancés)

````bash
PS C:\Users\kogay> Get-Service | Where-Object { $_.Status -eq 'Stopped' }

Status   Name               DisplayName
------   ----               -----------
Stopped  AarSvc_3264532     Agent Activation Runtime_3264532
Stopped  ALG                Service de la passerelle de la couc...
Stopped  AppIDSvc           Identité de l’application
Stopped  AppReadiness       Préparation des applications
Stopped  ApxSvc             Service proxy de périphérique audio...
Stopped  autotimesvc        Heure cellulaire
Stopped  AxInstSV           Programme d’installation ActiveX (A...
Stopped  BcastDVRUserSer... Service utilisateur de diffusion et...
Stopped  BDESVC             Service de chiffrement de lecteur B...
Stopped  CaptureService_... CaptureService_3264532
Stopped  CertPropSvc        Propagation du certificat
Stopped  ClipSVC            Service de licences de client (Clip...
Stopped  CloudBackupRest... Service de restauration et de sauve...
Stopped  COMSysApp          Application système COM+
Stopped  ConsentUxUserSv... Service utilisateur ConsentUX_3264532
Stopped  CredentialEnrol... CredentialEnrollmentManagerUserSvc_...
Stopped  dcsvc              Service de configuration (DC) déclaré
Stopped  defragsvc          Optimiser les lecteurs
Stopped  DeviceAssociati... DeviceAssociationBroker_3264532
Stopped  DevicePickerUse... DevicePicker_3264532
Stopped  diagsvc            Diagnostic Execution Service
Stopped  DmEnrollmentSvc    Service d'inscription de la gestion...
Stopped  dmwappushservice   Service de routage de messages Push...
Stopped  dot3svc            Configuration automatique de réseau...
Stopped  DsmSvc             Gestionnaire d’installation de péri...
Stopped  edgeupdate         Microsoft Edge Update Service (edge...
Stopped  edgeupdatem        Microsoft Edge Update Service (edge...
Stopped  EFS                Système de fichiers EFS (Encrypting...
Stopped  embeddedmode       Mode incorporé
Stopped  EntAppSvc          Service de gestion des applications...
Stopped  fdPHost            Hôte du fournisseur de découverte d...
Stopped  FDResPub           Publication des ressources de décou...
Stopped  fhsvc              Service d’historique des fichiers
Stopped  FontCache3.0.0.0   Cache de police de Windows Presenta...
Stopped  FrameServer        Serveur de trame de la Caméra Windows
Stopped  FrameServerMonitor Moniteur de serveur de trame Caméra...
Stopped  GameInputSvc       GameInput Service
Stopped  GoogleChromeEle... Google Chrome Elevation Service (Go...
Stopped  GoogleUpdaterIn... Service interne de mise à jour Goog...
Stopped  GoogleUpdaterSe... Service de mise à jour Google (Goog...
Stopped  GraphicsPerfSvc    GraphicsPerfSvc
Stopped  gupdate            Service Google Update (gupdate)
Stopped  gupdatem           Service Google Update (gupdatem)
Stopped  icssvc             Service Point d'accès sans fil mobi...
Stopped  IKEEXT             Modules de génération de clés IKE e...
Stopped  InventorySvc       Service d’Appraisal inventaire et c...
Stopped  IpxlatCfgSvc       Service de configuration de convers...
Stopped  KtmRm              Service KtmRm pour Distributed Tran...
Stopped  lltdsvc            Mappage de découverte de topologie ...
Stopped  lmhosts            Assistance NetBIOS sur TCP/IP
Stopped  LocalKdc           Centre local de distribution de clé...
Stopped  LxpSvc             Service d'expérience linguistique
Stopped  MapsBroker         Gestionnaire des cartes téléchargées
Stopped  McpManagementSe... McpManagementService
Stopped  MessagingServic... MessagingService_3264532
Stopped  MicrosoftEdgeEl... Microsoft Edge Elevation Service (M...
Stopped  MSDTC              Coordinateur de transactions distri...
Stopped  MSiSCSI            Service Initiateur iSCSI de Microsoft
Stopped  msiserver          Windows Installer
Stopped  NaturalAuthenti... Authentification naturelle
Stopped  NcaSvc             Assistant Connectivité réseau
Stopped  NcdAutoSetup       Configuration automatique des périp...
Stopped  Netlogon           Netlogon
Stopped  Netman             Connexions réseau
Stopped  NetSetupSvc        Service Configuration du réseau
Stopped  NetTcpPortSharing  Service de partage de ports Net.Tcp
Stopped  NgcCtnrSvc         Conteneur Microsoft Passport
Stopped  NgcSvc             Microsoft Passport
Stopped  NlaSvc             Connaissance des emplacements réseau
Stopped  OneDrive Update... OneDrive Updater Service
Stopped  P9RdrService_32... P9RdrService_3264532
Stopped  PenService_3264532 PenService_3264532
Stopped  perceptionsimul... Service de simulation de perception...
Stopped  PerfHost           Hôte de DLL de compteur de performance
Stopped  pla                Journaux & alertes de performance
Stopped  PolicyAgent        Agent de stratégie IPsec
Stopped  PrintDeviceConf... Service de configuration du périphé...
Stopped  PrintNotify        Extensions et notifications d’impri...
Stopped  PrintScanBroker... PrintScanBrokerService
Stopped  PrintWorkflowUs... PrintWorkflow_3264532
Stopped  PushToInstall      Service PushToInstall de Windows
Stopped  QWAVE              Expérience audio-vidéo haute qualit...
Stopped  RasAuto            Gestionnaire des connexions automat...
Stopped  refsdedupsvc       Service de déduplication ReFS
Stopped  RemoteAccess       Routage et accès distant
Stopped  RemoteRegistry     Registre à distance
Stopped  RetailDemo         Service de démo du magasin
Stopped  RpcLocator         Localisateur d’appels de procédure ...
Stopped  SCardSvr           Carte à puce
Stopped  ScDeviceEnum       Service d’énumération de périphériq...
Stopped  SCPolicySvc        Stratégie de retrait de la carte à ...
Stopped  SDRSVC             Sauvegarde Windows
Stopped  seclogon           Ouverture de session secondaire
Stopped  SEMgrSvc           Gestionnaires des paiements et des ...
Stopped  SensorDataService  Service Données de capteur
Stopped  SensrSvc           Service de surveillance des capteurs
Stopped  SessionEnv         Configuration des services Bureau à...
Stopped  SgrmBroker         Service Broker du moniteur d'exécut...
Stopped  shpamsvc           Shared PC Account Manager
Stopped  smphost            SMP de l’Espace de stockages Microsoft
Stopped  SmsRouter          Service Routeur SMS Microsoft Windows.
Stopped  SNMPTrap           Interruption SNMP
Stopped  sppsvc             Protection logicielle
Stopped  ssh-agent          OpenSSH Authentication Agent
Stopped  Steam Client Se... Steam Client Service
Stopped  svsvc              Vérificateur de points
Stopped  swprv              Fournisseur de cliché instantané de...
Stopped  TapiSrv            Téléphonie
Stopped  TermService        Services Bureau à distance
Stopped  TieringEngineSe... Gestion des niveaux de stockage
Stopped  TroubleshootingSvc Service de résolution des problèmes...
Stopped  TrustedInstaller   Programme d’installation pour les m...
Stopped  tzautoupdate       Programme de mise à jour automatiqu...
Stopped  UEIPSvc            User Experience Improvement Program
Stopped  UmRdpService       Redirecteur de port du mode utilisa...
Stopped  upnphost           Hôte de périphérique UPnP
Stopped  vds                Disque virtuel
Stopped  vgc                vgc
Stopped  vmcompute          Service de calcul hôte Hyper-V
Stopped  vmicguestinterface Interface de services d’invité Hyper-V
Stopped  vmicheartbeat      Service Pulsation Microsoft Hyper-V
Stopped  vmickvpexchange    Service Échange de données Microsof...
Stopped  vmicrdv            Service de virtualisation Bureau à ...
Stopped  vmicshutdown       Service Arrêt de l’invité Microsoft...
Stopped  vmictimesync       Service Synchronisation date/heure ...
Stopped  vmicvmsession      Service Hyper-V PowerShell Direct
Stopped  vmicvss            Requête du service VSS Hyper-V
Stopped  VSS                Cliché instantané des volumes
Stopped  W32Time            Temps Windows
Stopped  WaaSMedicSvc       WaaSMedicSvc
Stopped  WalletService      WalletService
Stopped  WarpJITSvc         Warp JIT Service
Stopped  wbengine           Service de moteur de sauvegarde en ...
Stopped  WbioSrvc           Service de biométrie Windows
Stopped  wcncsvc            Windows Connect Now - Registre de c...
Stopped  WdiServiceHost     Service hôte WDIServiceHost
Stopped  WebClient          WebClient
Stopped  Wecsvc             Collecteur d’événements de Windows
Stopped  WEPHOSTSVC         Service hôte du fournisseur de chif...
Stopped  wercplsupport      Prise en charge du Panneau de confi...
Stopped  WerSvc             Service de rapport d’erreurs Windows
Stopped  WFDSConMgrSvc      Service Wi-Fi Direct Service de ges...
Stopped  WiaRpc             Événements d’acquisition d’images f...
Stopped  WinRM              Gestion à distance de Windows (Gest...
Stopped  wisvc              Service Windows Insider
Stopped  wlidsvc            Assistant Connexion avec un compte ...
Stopped  wlpasvc            Service de l’Assistant de profil local
Stopped  WManSvc            Service de gestion de Windows
Stopped  WMPNetworkSvc      Service de partage réseau du Lecteu...
Stopped  workfolderssvc     Dossiers de travail
Stopped  WpcMonSvc          Contrôle parental
Stopped  WPDBusEnum         Service Énumérateur d’appareil mobile
Stopped  wuauserv           Windows Update
Stopped  WwanSvc            Service de configuration automatiqu...
Stopped  XblGameSave        Jeu sauvegardé sur Xbox Live
Stopped  XboxGipSvc         Xbox Accessory Management Service
Stopped  XboxNetApiSvc      Service de mise en réseau Xbox Live
````


Quantité de ram total de la machine

````bash
PS C:\Users\kogay> (Get-CimInstance Win32_ComputerSystem).TotalPhysicalMemory 
16469520384
````

Quantité de ram libre de la machine

````bash
PS C:\Users\kogay> (Get-CimInstance Win32_OperatingSystem).FreePhysicalMemory
5679716
````


CPU

````bash
PS C:\Users\kogay> (Get-WmiObject Win32_Processor).LoadPercentage
24
````


stockage peripherique

````bash
PS C:\Users\kogay> Get-CimInstance -ClassName Win32_DiskDrive | Select-Object -Property Model

Model
-----
SAMSUNG MZVL4512HBLU-00BTW
````


partition de stockage

````bash
PS C:\Users\kogay> Get-Partition


   DiskPath : \\?\scsi#disk&ven_nvme&prod_samsung_mzvl4512#5&24c35a8b&0&000000#{53f56307-b6bf-11d0-94f2-00a0c91efb8b}

PartitionNumber  DriveLetter Offset                                        Size Type
---------------  ----------- ------                                        ---- ----
1                           1048576                                     260 MB System
2                           273678336                                    16 MB Reserved
3                C           290455552                                475.67 GB Basic
4                           511036096512                                  1 GB Recovery
````


espace disque dur

````bash
PS C:\Users\kogay> Get-Volume

DriveLetter FriendlyName FileSystemType DriveType HealthStatus OperationalStatus SizeRemaining      Size
----------- ------------ -------------- --------- ------------ ----------------- -------------      ----
C           Acer         NTFS           Fixed     Healthy      OK                    107.46 GB 475.67 GB
            Recovery     NTFS           Fixed     Healthy      OK                    428.83 MB   1024 MB
````


carte réseau

````bash
PS C:\Users\kogay> Get-NetAdapter

Name                      InterfaceDescription                    ifIndex Status       MacAddress             LinkSpeed
----                      --------------------                    ------- ------       ----------             ---------
Ethernet 4                VirtualBox Host-Only Ethernet Adap...#2      23 Up           0A-00-27-00-00-17         1 Gbps
Wi-Fi                     MediaTek Wi-Fi 6 MT7921 Wireless LAN...      21 Up           C0-35-32-A0-2A-79     866.7 Mbps
Connexion réseau Bluet... Bluetooth Device (Personal Area Netw...      12 Disconnected C0-35-32-A0-2A-7A         3 Mbps
Ethernet 5                VirtualBox Host-Only Ethernet Adapter         4 Up           0A-00-27-00-00-04         1 Gbps
Ethernet                  Realtek PCIe GbE Family Controller            3 Disconnected 40-C2-BA-F8-26-93          0 bps
````



connexion réseau

````bash
PS C:\Users\kogay> Get-NetTCPConnection -State Established

LocalAddress                        LocalPort RemoteAddress                       RemotePort State       AppliedSetting
------------                        --------- -------------                       ---------- -----       --------------
2a01:cb19:18c:c700:ec96:8a3e:723... 60108     2606:4700:90:0:f22e:fbec:5bed:a9b9  443        Established Internet
2a01:cb19:18c:c700:ec96:8a3e:723... 60107     2606:4700:90:0:f22e:fbec:5bed:a9b9  443        Established Internet
2a01:cb19:18c:c700:ec96:8a3e:723... 60090     2606:4700:4400::ac40:9bd1           443        Established Internet
2a01:cb19:18c:c700:ec96:8a3e:723... 59759     2603:1026:100:1a::2                 443        Established Internet
2a01:cb19:18c:c700:ec96:8a3e:723... 59035     2a00:1450:400c:c06::bc              5228       Established Internet
::1                                 58986     ::1                                 5426       Established Internet
::1                                 58985     ::1                                 5426       Established Internet
2a01:cb19:18c:c700:ec96:8a3e:723... 58948     2600:1901:1:a8::                    443        Established Internet
::1                                 58887     ::1                                 4449       Established Internet
::1                                 58886     ::1                                 15150      Established Internet
::1                                 58885     ::1                                 4343       Established Internet
::1                                 58878     ::1                                 5426       Established Internet
::1                                 58875     ::1                                 5426       Established Internet
::1                                 58870     ::1                                 5426       Established Internet
::1                                 58869     ::1                                 5426       Established Internet
::1                                 58845     ::1                                 5141       Established Internet
::1                                 58833     ::1                                 15150      Established Internet
::1                                 15150     ::1                                 58886      Established Internet
::1                                 15150     ::1                                 58833      Established Internet
::1                                 5426      ::1                                 58986      Established Internet
::1                                 5426      ::1                                 58985      Established Internet
::1                                 5426      ::1                                 58878      Established Internet
::1                                 5426      ::1                                 58875      Established Internet
::1                                 5426      ::1                                 58870      Established Internet
::1                                 5426      ::1                                 58869      Established Internet
::1                                 5141      ::1                                 58845      Established Internet
::1                                 4449      ::1                                 58887      Established Internet
::1                                 4343      ::1                                 58885      Established Internet
192.168.1.18                        60112     20.189.173.26                       443        Established Internet
192.168.1.18                        60099     104.75.232.13                       80         Established Internet
192.168.1.18                        60063     140.82.112.25                       443        Established Internet
127.0.0.1                           59184     127.0.0.1                           5141       Established Internet
192.168.1.18                        58906     162.159.133.234                     443        Established Internet
192.168.1.18                        58836     20.199.120.182                      443        Established Internet
127.0.0.1                           58334     127.0.0.1                           51779      Established Internet
127.0.0.1                           58333     127.0.0.1                           46753      Established Internet
127.0.0.1                           51779     127.0.0.1                           58334      Established Internet
127.0.0.1                           51648     127.0.0.1                           51647      Established Internet
127.0.0.1                           51647     127.0.0.1                           51648      Established Internet
127.0.0.1                           49673     127.0.0.1                           49672      Established Internet
127.0.0.1                           49672     127.0.0.1                           49673      Established Internet
192.168.1.18                        49442     20.199.120.85                       443        Established Internet
127.0.0.1                           46753     127.0.0.1                           58333      Established Internet
127.0.0.1                           5141      127.0.0.1                           59184      Established Internet
````


utilisateurs de la machine

````bash
PS C:\Users\kogay> net user

comptes d’utilisateurs de \\KOGAYE

-------------------------------------------------------------------------------
Administrateur           Amir                     DefaultAccount
Invité                   WDAGUtilityAccount
La commande s’est terminée correctement.
````


Heure de login

````bash
PS C:\Users\kogay> (get-date) – (gcim Win32_OperatingSystem). LastBootUpTime


Days              : 6
Hours             : 1
Minutes           : 38
Seconds           : 3
Milliseconds      : 724
Ticks             : 5242837249502
TotalDays         : 6,06809866840509
TotalHours        : 145,634368041722
TotalMinutes      : 8738,06208250333
TotalSeconds      : 524283,7249502
TotalMilliseconds : 524283724,9502
````


Les processus en cours d'execution

````bash
PS C:\Users\kogay> Get-Process | Select-Object Name, Id, @{Name="UserName";Expression={(Get-WmiObject Win32_Process -Filter "ProcessId = '$($_.Id)'").GetOwner().User}}

Name       Id UserName
----       -- --------
AAADSvc  5264
ACCStd  22960 Amir
ACCSvc   5244
ACCU... 14564 Amir
Acer... 10380
Acer...  5292
Acer...  5436
Acer...  5308
Acer...  5324
Acer...  9084 Amir
Acer... 12932 Amir
Acer... 13008 Amir
Acer... 15168 Amir
Acer...  6448
Acer...  5316
Acer...  2992
Acer... 20984
Acer...  4652
ADES... 18600
ADES...  5300
Aggr...  8440
amdf...  2964
amdow    1380 Amir
AMDR... 14232 Amir
AMDR... 21088 Amir
Appl... 13432 Amir
AQAU...  8556 Amir
ARTA...  5272
atie... 22492
atie...  2972
audiodg  9960
back... 32648 Amir
chrome   4680 Amir
chrome  10612 Amir
chrome  13180 Amir
chrome  15908 Amir
chrome  17544 Amir
chrome  19648 Amir
chrome  20484 Amir
chrome  22288 Amir
chrome  23444 Amir
chrome  24104 Amir
chrome  25956 Amir
chrome  28172 Amir
chrome  28476 Amir
chrome  28764 Amir
chrome  30140 Amir
chrome  31336 Amir
chrome  31372 Amir
chrome  34120 Amir
chrome  34948 Amir
cncmd   12308 Amir
conhost  3436
conhost  6392
conhost  6444
conhost  6740
conhost  6916
conhost  7128
conhost  7468
conhost  7612
conhost 35184 Amir
cras... 35892
Cros... 12232 Amir
csrss    1052
csrss   12564
ctfmon  17848 Amir
dasHost  3100
Discord  8176
Discord  8308 Amir
Discord 11888
Discord 12360 Amir
Discord 15832 Amir
Discord 20540
dllhost 13940 Amir
dllhost 16600 Amir
dllhost 17368 Amir
dwm      8580
expl... 21024 Amir
File... 20856 Amir
File... 19076
````



déterminer quel utilisateur est le propriétaire du fichier

````bash
PS C:\Users\kogay> (Get-Acl "C:\Users\kogay\.lunarclient\").Owner
KOGAYE\Amir
````


Uptime (afficher l'heure/la date de l'allumage de la machine)

````bash
PS C:\Users\kogay> (Get-CimInstance Win32_OperatingSystem).LastBootUpTime

vendredi 14 janvier 2024 18:45:52
````








Device (afficher le modèle du processeur de la machine)

````bash
PS C:\Users\kogay> (Get-WmiObject Win32_Processor).Name
AMD Ryzen 7 5700U with Radeon Graphics
````




Version OS

````bash
PS C:\Users\kogay> (Get-WmiObject Win32_OperatingSystem).Caption
Microsoft Windows 11 Famille
````



Lister les connexions actives

````bash
PS C:\Users\kogay> Get-NetTCPConnection | Select-Object LocalAddress, LocalPort, RemoteAddress, RemotePort, State, OwningProcess


LocalAddress  : ::
LocalPort     : 60139
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 31336

LocalAddress  : ::
LocalPort     : 60135
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 31336

LocalAddress  : ::
LocalPort     : 60113
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 31336

LocalAddress  : ::
LocalPort     : 60107
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 31336

LocalAddress  : ::
LocalPort     : 60104
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : ::
LocalPort     : 60100
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : ::
LocalPort     : 60098
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : ::
LocalPort     : 60097
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : ::
LocalPort     : 59762
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : ::
LocalPort     : 59759
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : ::
LocalPort     : 58986
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 16572

LocalAddress  : ::
LocalPort     : 58985
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 16572

LocalAddress  : ::
LocalPort     : 58948
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 20540

LocalAddress  : ::
LocalPort     : 58887
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 13008

LocalAddress  : ::
LocalPort     : 58886
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 13008

LocalAddress  : ::
LocalPort     : 58885
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 13008

LocalAddress  : ::
LocalPort     : 58878
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 16572

LocalAddress  : ::
LocalPort     : 58875
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 16572

LocalAddress  : ::
LocalPort     : 58870
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 16572

LocalAddress  : ::
LocalPort     : 58869
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 16572

LocalAddress  : ::
LocalPort     : 58845
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 13008

LocalAddress  : ::
LocalPort     : 58833
RemoteAddress : ::
RemotePort    : 0
State         : Bound
OwningProcess : 12932

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 60139
RemoteAddress : 2600:1901:0:47fc::
RemotePort    : 443
State         : Established
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 60135
RemoteAddress : 2606:4700:4400::ac40:9bd1
RemotePort    : 443
State         : Established
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 60113
RemoteAddress : 2a00:1450:400c:c0a::bc
RemotePort    : 5228
State         : Established
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 60107
RemoteAddress : 2606:4700:90:0:f22e:fbec:5bed:a9b9
RemotePort    : 443
State         : Established
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 60100
RemoteAddress : 2620:1ec:bdf::42
RemotePort    : 443
State         : CloseWait
OwningProcess : 21060

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 60097
RemoteAddress : 2620:1ec:bdf::254
RemotePort    : 443
State         : CloseWait
OwningProcess : 21060

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59762
RemoteAddress : 2603:1061:11:1::254
RemotePort    : 443
State         : CloseWait
OwningProcess : 21060

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59337
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59336
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59329
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59328
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59327
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59324
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59323
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59322
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59321
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59314
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59313
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59312
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59311
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59310
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59309
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59308
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59307
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59306
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59305
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59304
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59303
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59302
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59301
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59300
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59299
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59298
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59297
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59296
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59295
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59294
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59293
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59289
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59288
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59287
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59286
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59285
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59284
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59268
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59267
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59266
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59265
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59264
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59263
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59262
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59261
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59260
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59259
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59258
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59257
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59255
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59254
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59253
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59252
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59251
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59250
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59249
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59248
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59247
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : fe80::b98:66e1:5292:6c9e%21
LocalPort     : 59246
RemoteAddress : fe80::8ef8:13ff:fe59:1180%21
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59245
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59232
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59231
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59223
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59222
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59221
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 59220
RemoteAddress : 2a01:cb19:18c:c700:8ef8:13ff:fe59:1180
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : ::
LocalPort     : 58995
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 5308

LocalAddress  : ::1
LocalPort     : 58986
RemoteAddress : ::1
RemotePort    : 5426
State         : Established
OwningProcess : 16572

LocalAddress  : ::1
LocalPort     : 58985
RemoteAddress : ::1
RemotePort    : 5426
State         : Established
OwningProcess : 16572

LocalAddress  : 2a01:cb19:18c:c700:ec96:8a3e:723b:9de6
LocalPort     : 58948
RemoteAddress : 2600:1901:1:a8::
RemotePort    : 443
State         : Established
OwningProcess : 20540

LocalAddress  : ::1
LocalPort     : 58887
RemoteAddress : ::1
RemotePort    : 4449
State         : Established
OwningProcess : 13008

LocalAddress  : ::1
LocalPort     : 58886
RemoteAddress : ::1
RemotePort    : 15150
State         : Established
OwningProcess : 13008

LocalAddress  : ::1
LocalPort     : 58885
RemoteAddress : ::1
RemotePort    : 4343
State         : Established
OwningProcess : 13008

LocalAddress  : ::1
LocalPort     : 58878
RemoteAddress : ::1
RemotePort    : 5426
State         : Established
OwningProcess : 16572

LocalAddress  : ::1
LocalPort     : 58875
RemoteAddress : ::1
RemotePort    : 5426
State         : Established
OwningProcess : 16572

LocalAddress  : ::1
LocalPort     : 58870
RemoteAddress : ::1
RemotePort    : 5426
State         : Established
OwningProcess : 16572

LocalAddress  : ::1
LocalPort     : 58869
RemoteAddress : ::1
RemotePort    : 5426
State         : Established
OwningProcess : 16572

LocalAddress  : ::1
LocalPort     : 58845
RemoteAddress : ::1
RemotePort    : 5141
State         : Established
OwningProcess : 13008

LocalAddress  : ::1
LocalPort     : 58833
RemoteAddress : ::1
RemotePort    : 15150
State         : Established
OwningProcess : 12932

LocalAddress  : ::
LocalPort     : 54235
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 4

LocalAddress  : ::
LocalPort     : 49688
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 1304

LocalAddress  : ::
LocalPort     : 49671
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 4848

LocalAddress  : ::
LocalPort     : 49667
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 2980

LocalAddress  : ::
LocalPort     : 49666
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 2688

LocalAddress  : ::
LocalPort     : 49665
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 1192

LocalAddress  : ::
LocalPort     : 49664
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 1368

LocalAddress  : ::
LocalPort     : 46760
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 20984

LocalAddress  : ::1
LocalPort     : 42050
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 16876

LocalAddress  : ::1
LocalPort     : 15150
RemoteAddress : ::1
RemotePort    : 58886
State         : Established
OwningProcess : 12932

LocalAddress  : ::1
LocalPort     : 15150
RemoteAddress : ::1
RemotePort    : 58833
State         : Established
OwningProcess : 12932

LocalAddress  : ::1
LocalPort     : 15150
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 12932

LocalAddress  : ::1
LocalPort     : 13337
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 5424

LocalAddress  : ::1
LocalPort     : 5426
RemoteAddress : ::1
RemotePort    : 58986
State         : Established
OwningProcess : 4

LocalAddress  : ::1
LocalPort     : 5426
RemoteAddress : ::1
RemotePort    : 58985
State         : Established
OwningProcess : 4

LocalAddress  : ::1
LocalPort     : 5426
RemoteAddress : ::1
RemotePort    : 58878
State         : Established
OwningProcess : 4

LocalAddress  : ::1
LocalPort     : 5426
RemoteAddress : ::1
RemotePort    : 58875
State         : Established
OwningProcess : 4

LocalAddress  : ::1
LocalPort     : 5426
RemoteAddress : ::1
RemotePort    : 58870
State         : Established
OwningProcess : 4

LocalAddress  : ::1
LocalPort     : 5426
RemoteAddress : ::1
RemotePort    : 58869
State         : Established
OwningProcess : 4

LocalAddress  : ::
LocalPort     : 5426
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 4

LocalAddress  : ::1
LocalPort     : 5141
RemoteAddress : ::1
RemotePort    : 58845
State         : Established
OwningProcess : 5324

LocalAddress  : ::
LocalPort     : 5141
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 5324

LocalAddress  : ::1
LocalPort     : 4449
RemoteAddress : ::1
RemotePort    : 58887
State         : Established
OwningProcess : 5292

LocalAddress  : ::
LocalPort     : 4449
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 5292

LocalAddress  : ::1
LocalPort     : 4343
RemoteAddress : ::1
RemotePort    : 58885
State         : Established
OwningProcess : 10380

LocalAddress  : ::
LocalPort     : 4343
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 10380

LocalAddress  : ::
LocalPort     : 445
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 4

LocalAddress  : ::
LocalPort     : 135
RemoteAddress : ::
RemotePort    : 0
State         : Listen
OwningProcess : 1620

LocalAddress  : 0.0.0.0
LocalPort     : 60145
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 5488

LocalAddress  : 0.0.0.0
LocalPort     : 60137
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 31336

LocalAddress  : 0.0.0.0
LocalPort     : 60103
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : 0.0.0.0
LocalPort     : 60102
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : 0.0.0.0
LocalPort     : 60101
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : 0.0.0.0
LocalPort     : 60099
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 21060

LocalAddress  : 0.0.0.0
LocalPort     : 59536
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 8872

LocalAddress  : 0.0.0.0
LocalPort     : 59535
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 8872

LocalAddress  : 0.0.0.0
LocalPort     : 59184
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 8556

LocalAddress  : 0.0.0.0
LocalPort     : 58906
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 20540

LocalAddress  : 0.0.0.0
LocalPort     : 58836
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 25012

LocalAddress  : 0.0.0.0
LocalPort     : 58334
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 12932

LocalAddress  : 0.0.0.0
LocalPort     : 58333
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 12932

LocalAddress  : 0.0.0.0
LocalPort     : 51648
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 20984

LocalAddress  : 0.0.0.0
LocalPort     : 49673
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 5300

LocalAddress  : 0.0.0.0
LocalPort     : 49442
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Bound
OwningProcess : 5364

LocalAddress  : 127.0.0.1
LocalPort     : 65444
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 6892

LocalAddress  : 192.168.1.18
LocalPort     : 60145
RemoteAddress : 104.208.16.90
RemotePort    : 443
State         : Established
OwningProcess : 5488

LocalAddress  : 192.168.1.18
LocalPort     : 60143
RemoteAddress : 40.79.189.59
RemotePort    : 443
State         : TimeWait
OwningProcess : 0

LocalAddress  : 192.168.1.18
LocalPort     : 60137
RemoteAddress : 140.82.114.26
RemotePort    : 443
State         : Established
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 60099
RemoteAddress : 104.75.232.13
RemotePort    : 80
State         : CloseWait
OwningProcess : 21060

LocalAddress  : 192.168.1.18
LocalPort     : 59318
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59317
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59316
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59315
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59283
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59282
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59281
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59280
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59279
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59278
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59277
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59276
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59275
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59274
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59273
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59272
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59271
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59270
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59269
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59244
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59243
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59242
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59241
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59240
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59239
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59238
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59237
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59236
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59235
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59230
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59229
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59228
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 192.168.1.18
LocalPort     : 59227
RemoteAddress : 192.168.1.1
RemotePort    : 53
State         : FinWait2
OwningProcess : 31336

LocalAddress  : 127.0.0.1
LocalPort     : 59184
RemoteAddress : 127.0.0.1
RemotePort    : 5141
State         : Established
OwningProcess : 8556

LocalAddress  : 192.168.1.18
LocalPort     : 58906
RemoteAddress : 162.159.133.234
RemotePort    : 443
State         : Established
OwningProcess : 20540

LocalAddress  : 192.168.1.18
LocalPort     : 58836
RemoteAddress : 20.199.120.182
RemotePort    : 443
State         : Established
OwningProcess : 25012

LocalAddress  : 127.0.0.1
LocalPort     : 58334
RemoteAddress : 127.0.0.1
RemotePort    : 51779
State         : Established
OwningProcess : 12932

LocalAddress  : 127.0.0.1
LocalPort     : 58333
RemoteAddress : 127.0.0.1
RemotePort    : 46753
State         : Established
OwningProcess : 12932

LocalAddress  : 127.0.0.1
LocalPort     : 51782
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 5300

LocalAddress  : 127.0.0.1
LocalPort     : 51781
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 5300

LocalAddress  : 127.0.0.1
LocalPort     : 51780
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 5300

LocalAddress  : 127.0.0.1
LocalPort     : 51779
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 5300

LocalAddress  : 127.0.0.1
LocalPort     : 51779
RemoteAddress : 127.0.0.1
RemotePort    : 58334
State         : Established
OwningProcess : 5300

LocalAddress  : 127.0.0.1
LocalPort     : 51648
RemoteAddress : 127.0.0.1
RemotePort    : 51647
State         : Established
OwningProcess : 20984

LocalAddress  : 127.0.0.1
LocalPort     : 51647
RemoteAddress : 127.0.0.1
RemotePort    : 51648
State         : Established
OwningProcess : 20984

LocalAddress  : 0.0.0.0
LocalPort     : 49688
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 1304

LocalAddress  : 127.0.0.1
LocalPort     : 49673
RemoteAddress : 127.0.0.1
RemotePort    : 49672
State         : Established
OwningProcess : 5300

LocalAddress  : 127.0.0.1
LocalPort     : 49672
RemoteAddress : 127.0.0.1
RemotePort    : 49673
State         : Established
OwningProcess : 5300

LocalAddress  : 0.0.0.0
LocalPort     : 49671
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 4848

LocalAddress  : 0.0.0.0
LocalPort     : 49667
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 2980

LocalAddress  : 0.0.0.0
LocalPort     : 49666
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 2688

LocalAddress  : 0.0.0.0
LocalPort     : 49665
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 1192

LocalAddress  : 0.0.0.0
LocalPort     : 49664
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 1368

LocalAddress  : 192.168.1.18
LocalPort     : 49442
RemoteAddress : 20.199.120.85
RemotePort    : 443
State         : Established
OwningProcess : 5364

LocalAddress  : 127.0.0.1
LocalPort     : 46753
RemoteAddress : 127.0.0.1
RemotePort    : 58333
State         : Established
OwningProcess : 20984

LocalAddress  : 127.0.0.1
LocalPort     : 46753
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 20984

LocalAddress  : 127.0.0.1
LocalPort     : 19443
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 5436

LocalAddress  : 127.0.0.1
LocalPort     : 15152
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 6448

LocalAddress  : 127.0.0.1
LocalPort     : 13344
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 10668

LocalAddress  : 127.0.0.1
LocalPort     : 13331
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 9272

LocalAddress  : 127.0.0.1
LocalPort     : 9993
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 12932

LocalAddress  : 127.0.0.1
LocalPort     : 6463
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 8176

LocalAddress  : 127.0.0.1
LocalPort     : 5141
RemoteAddress : 127.0.0.1
RemotePort    : 59184
State         : Established
OwningProcess : 5324

LocalAddress  : 0.0.0.0
LocalPort     : 5040
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 9520

LocalAddress  : 127.0.0.1
LocalPort     : 1337
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 5424

LocalAddress  : 192.168.56.1
LocalPort     : 139
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 4

LocalAddress  : 192.168.1.18
LocalPort     : 139
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 4

LocalAddress  : 10.1.1.100
LocalPort     : 139
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 4

LocalAddress  : 0.0.0.0
LocalPort     : 135
RemoteAddress : 0.0.0.0
RemotePort    : 0
State         : Listen
OwningProcess : 1620
````


En savoir plus sur le chemin vers un programme

````bash
(Get-Process -Id <ID Processus>).Path
````


En savoir plus sur le proprietaire du programme

````bash
(Get-Process -Id <ID Processus>).Path).Owner
````



Utilise la commande Invoke-RestMethod pour obtenir des informations sur une adresse IP

````bash
Invoke-RestMethod -Method Get -Uri http://ip-api.com/json/<ADRESSE IP>
````



avoir le delai d'une adresse IP

````bash
ping <ADRESSE IP>
````





