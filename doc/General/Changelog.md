## 1.55
*(2019-09-02)*

A big thank you to the following 31 contributors this last month:

  - murrant (16)
  - PipoCanaja (9)
  - Jellyfrog (4)
  - SniperVegeta (3)
  - SourceDoctor (3)
  - hanserasmus (3)
  - deajan (2)
  - garysteers (2)
  - jasoncheng7115 (2)
  - rsys-dev (2)
  - VVelox (2)
  - TvL2386 (2)
  - voipmeister (1)
  - dsgagi (1)
  - jvit (1)
  - frankmcc (1)
  - FTBZ (1)
  - h-barnhart (1)
  - arrmo (1)
  - nsn-amagruder (1)
  - SteFletcher (1)
  - soto2080 (1)
  - opalivan (1)
  - erotel (1)
  - martijn-schmidt (1)
  - XioNoX (1)
  - Serazio (1)
  - rdezavalia (1)
  - BrianSidebotham (1)
  - fbourqui (1)
  - Munzy (1)

#### Feature
* Added Graylog to device overview and log level filter mechanism ([#10509](https://github.com/librenms/librenms/pull/10509)) - [rsys-dev](https://github.com/rsys-dev)
* Allow adding custom quick links to device navigation ([#10403](https://github.com/librenms/librenms/pull/10403)) - [jasoncheng7115](https://github.com/jasoncheng7115)
* Simple linear port graph prediction ([#10520](https://github.com/librenms/librenms/pull/10520)) - [murrant](https://github.com/murrant)
* Allow filtering of Health sensor discovery ([#10485](https://github.com/librenms/librenms/pull/10485)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Security
* Fix html injection in user fields ([#10535](https://github.com/librenms/librenms/pull/10535)) - [murrant](https://github.com/murrant)
* Update the docs to reflect various updates to SNMP/local bits ([#10507](https://github.com/librenms/librenms/pull/10507)) - [VVelox](https://github.com/VVelox)

#### Device
* Added AIX detection running std snmpd or net-snmp ([#10569](https://github.com/librenms/librenms/pull/10569)) - [fbourqui](https://github.com/fbourqui)
* Added more DELL switches in order to get proper CPU stats ([#10529](https://github.com/librenms/librenms/pull/10529)) - [rdezavalia](https://github.com/rdezavalia)
* Fixed Junos port/vlan relationships for els and non-els based software ([#10321](https://github.com/librenms/librenms/pull/10321)) - [Serazio](https://github.com/Serazio)
* Add serial/model/version polling for Sentry4 MIB ([#10432](https://github.com/librenms/librenms/pull/10432)) - [XioNoX](https://github.com/XioNoX)
* Convert opengear to YAML-based discovery, add some new sensors, add test data ([#10553](https://github.com/librenms/librenms/pull/10553)) - [martijn-schmidt](https://github.com/martijn-schmidt)
* Added support Ericsson MINI-LINK ([#10546](https://github.com/librenms/librenms/pull/10546)) - [erotel](https://github.com/erotel)
* NXOS can build FDB table too ([#10522](https://github.com/librenms/librenms/pull/10522)) - [soto2080](https://github.com/soto2080)
* Reduce discovery snmp load of Cisco VTP vlans module ([#10510](https://github.com/librenms/librenms/pull/10510)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added new device - Exagrid ([#10496](https://github.com/librenms/librenms/pull/10496)) - [nsn-amagruder](https://github.com/nsn-amagruder)
* Added support for OS dd-wrt ([#10500](https://github.com/librenms/librenms/pull/10500)) - [arrmo](https://github.com/arrmo)
* Watchguard Fireware is FirewareOS in oxidized ([#10494](https://github.com/librenms/librenms/pull/10494)) - [deajan](https://github.com/deajan)
* Fixed missing FW and Serials in Dlink ([#10481](https://github.com/librenms/librenms/pull/10481)) - [hanserasmus](https://github.com/hanserasmus)
* Added definition for Cisco SB SG250X ([#10472](https://github.com/librenms/librenms/pull/10472)) - [PipoCanaja](https://github.com/PipoCanaja)
* Extended RecoveryOS Definition ([#10475](https://github.com/librenms/librenms/pull/10475)) - [h-barnhart](https://github.com/h-barnhart)

#### Webui
* Show a hint that trend line exists ([#10573](https://github.com/librenms/librenms/pull/10573)) - [murrant](https://github.com/murrant)
* Convert About page to Laravel ([#10551](https://github.com/librenms/librenms/pull/10551)) - [Jellyfrog](https://github.com/Jellyfrog)
* Sort Devices and Groups in Alert Rules 'map to' droplist ([#10530](https://github.com/librenms/librenms/pull/10530)) - [SourceDoctor](https://github.com/SourceDoctor)
* Fixed menu links that used to redirect to # ([#10540](https://github.com/librenms/librenms/pull/10540)) - [Jellyfrog](https://github.com/Jellyfrog)
* Fix alert log status ([#10524](https://github.com/librenms/librenms/pull/10524)) - [SniperVegeta](https://github.com/SniperVegeta)
* Fix public status location ([#10526](https://github.com/librenms/librenms/pull/10526)) - [murrant](https://github.com/murrant)
* Fix Syslog widget ([#10516](https://github.com/librenms/librenms/pull/10516)) - [murrant](https://github.com/murrant)
* Add device group filter to widgets ([#9692](https://github.com/librenms/librenms/pull/9692)) - [Jellyfrog](https://github.com/Jellyfrog)
* Nfdump support for with NFSen ([#10376](https://github.com/librenms/librenms/pull/10376)) - [VVelox](https://github.com/VVelox)
* Laravel 5.8 and updated dependencies ([#10489](https://github.com/librenms/librenms/pull/10489)) - [murrant](https://github.com/murrant)
* Add an option to hide Location column in Alerts widget ([#10482](https://github.com/librenms/librenms/pull/10482)) - [dsgagi](https://github.com/dsgagi)
* Update services.inc.php ([#10486](https://github.com/librenms/librenms/pull/10486)) - [SniperVegeta](https://github.com/SniperVegeta)
* Check PHP version first ([#10473](https://github.com/librenms/librenms/pull/10473)) - [murrant](https://github.com/murrant)
* Add resources/views/menu/ to .gitignore ([#10479](https://github.com/librenms/librenms/pull/10479)) - [frankmcc](https://github.com/frankmcc)

#### Graphs
* Fix some graphs having the wrong timeframe ([#10554](https://github.com/librenms/librenms/pull/10554)) - [murrant](https://github.com/murrant)
* Added Cisco-voice IP graphs ([#10538](https://github.com/librenms/librenms/pull/10538)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fixed unauth graphs not working ([#10483](https://github.com/librenms/librenms/pull/10483)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Applications
* Smart -power on hour -  view fix ([#10466](https://github.com/librenms/librenms/pull/10466)) - [SourceDoctor](https://github.com/SourceDoctor)

#### Api
* Ports API: Workaround for ifNames with slashes ([#10502](https://github.com/librenms/librenms/pull/10502)) - [murrant](https://github.com/murrant)
* Allowed device_ids as INT or as STRING ([#10536](https://github.com/librenms/librenms/pull/10536)) - [TvL2386](https://github.com/TvL2386)
* Move API routing to Laravel ([#10457](https://github.com/librenms/librenms/pull/10457)) - [murrant](https://github.com/murrant)

#### Alerting
* Include alert ID in alert templates ([#10552](https://github.com/librenms/librenms/pull/10552)) - [SniperVegeta](https://github.com/SniperVegeta)

#### Discovery
* Allow num_oid to use OCTET STRING indexes ([#10410](https://github.com/librenms/librenms/pull/10410)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Polling
* Add inbit and outbit rate to auxiliary datastores. ([#10512](https://github.com/librenms/librenms/pull/10512)) - [SteFletcher](https://github.com/SteFletcher)

#### Bug
* Fix testing fping output when the LibreNMS user doesn't have a valid … ([#10567](https://github.com/librenms/librenms/pull/10567)) - [BrianSidebotham](https://github.com/BrianSidebotham)
* Fix Graylog level -1 display ([#10560](https://github.com/librenms/librenms/pull/10560)) - [murrant](https://github.com/murrant)
* Use PHP sys_temp_dir by default ([#10428](https://github.com/librenms/librenms/pull/10428)) - [deajan](https://github.com/deajan)
* Fix ipv6_network_id query for `null` context_name ([#10544](https://github.com/librenms/librenms/pull/10544)) - [garysteers](https://github.com/garysteers)
* Fixed Incorrect device match in Graylog ([#10501](https://github.com/librenms/librenms/pull/10501)) - [rsys-dev](https://github.com/rsys-dev)
* Fix .env with number symbols ([#10497](https://github.com/librenms/librenms/pull/10497)) - [murrant](https://github.com/murrant)

#### Documentation
* Update FAQ.md ([#10513](https://github.com/librenms/librenms/pull/10513)) - [hanserasmus](https://github.com/hanserasmus)
* Update Applications.md for mysql ([#10549](https://github.com/librenms/librenms/pull/10549)) - [opalivan](https://github.com/opalivan)
* Fixes the invalid json of the example curl statement ([#10537](https://github.com/librenms/librenms/pull/10537)) - [TvL2386](https://github.com/TvL2386)
* Update Installation-CentOS-7-Apache.md ([#10504](https://github.com/librenms/librenms/pull/10504)) - [hanserasmus](https://github.com/hanserasmus)
* Typo fix, minor textual changes in support docs ([#10499](https://github.com/librenms/librenms/pull/10499)) - [voipmeister](https://github.com/voipmeister)
* Fix installation instructions for Ubuntu-1804 ([#10488](https://github.com/librenms/librenms/pull/10488)) - [jvit](https://github.com/jvit)
* Oxidized - Recover a configuration of a disabled/removed device ([#10469](https://github.com/librenms/librenms/pull/10469)) - [FTBZ](https://github.com/FTBZ)
* Missing an I from Input ([#10474](https://github.com/librenms/librenms/pull/10474)) - [Munzy](https://github.com/Munzy)

#### Translation
* Update zh-TW.json for about page ([#10558](https://github.com/librenms/librenms/pull/10558)) - [jasoncheng7115](https://github.com/jasoncheng7115)

#### Misc
* Automatically cleanup plugin-table from removed plugins ([#10533](https://github.com/librenms/librenms/pull/10533)) - [SourceDoctor](https://github.com/SourceDoctor)
* Remove legacy auth usage of $_SESSION ([#10491](https://github.com/librenms/librenms/pull/10491)) - [murrant](https://github.com/murrant)


## 1.55
*(2019-09-02)*

A big thank you to the following 31 contributors this last month:

  - murrant (16)
  - PipoCanaja (9)
  - Jellyfrog (4)
  - SourceDoctor (3)
  - hanserasmus (3)
  - SniperVegeta (3)
  - VVelox (2)
  - rsys-dev (2)
  - jasoncheng7115 (2)
  - garysteers (2)
  - deajan (2)
  - TvL2386 (2)
  - Serazio (1)
  - h-barnhart (1)
  - FTBZ (1)
  - frankmcc (1)
  - jvit (1)
  - dsgagi (1)
  - voipmeister (1)
  - arrmo (1)
  - nsn-amagruder (1)
  - opalivan (1)
  - soto2080 (1)
  - XioNoX (1)
  - erotel (1)
  - SteFletcher (1)
  - fbourqui (1)
  - BrianSidebotham (1)
  - rdezavalia (1)
  - martijn-schmidt (1)
  - Munzy (1)

#### Feature
* Allow adding custom quick links to device navigation ([#10403](https://github.com/librenms/librenms/pull/10403)) - [jasoncheng7115](https://github.com/jasoncheng7115)
* Simple linear port graph prediction ([#10520](https://github.com/librenms/librenms/pull/10520)) - [murrant](https://github.com/murrant)
* Allow filtering of Health sensor discovery ([#10485](https://github.com/librenms/librenms/pull/10485)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Security
* Fix html injection in user fields ([#10535](https://github.com/librenms/librenms/pull/10535)) - [murrant](https://github.com/murrant)
* Update the docs to reflect various updates to SNMP/local bits ([#10507](https://github.com/librenms/librenms/pull/10507)) - [VVelox](https://github.com/VVelox)

#### Device
* Added AIX detection running std snmpd or net-snmp ([#10569](https://github.com/librenms/librenms/pull/10569)) - [fbourqui](https://github.com/fbourqui)
* Added more DELL switches in order to get proper CPU stats ([#10529](https://github.com/librenms/librenms/pull/10529)) - [rdezavalia](https://github.com/rdezavalia)
* Fixed Junos port/vlan relationships for els and non-els based software ([#10321](https://github.com/librenms/librenms/pull/10321)) - [Serazio](https://github.com/Serazio)
* Add serial/model/version polling for Sentry4 MIB ([#10432](https://github.com/librenms/librenms/pull/10432)) - [XioNoX](https://github.com/XioNoX)
* Convert opengear to YAML-based discovery, add some new sensors, add test data ([#10553](https://github.com/librenms/librenms/pull/10553)) - [martijn-schmidt](https://github.com/martijn-schmidt)
* Added support Ericsson MINI-LINK ([#10546](https://github.com/librenms/librenms/pull/10546)) - [erotel](https://github.com/erotel)
* NXOS can build FDB table too ([#10522](https://github.com/librenms/librenms/pull/10522)) - [soto2080](https://github.com/soto2080)
* Reduce discovery snmp load of Cisco VTP vlans module ([#10510](https://github.com/librenms/librenms/pull/10510)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added new device - Exagrid ([#10496](https://github.com/librenms/librenms/pull/10496)) - [nsn-amagruder](https://github.com/nsn-amagruder)
* Added support for OS dd-wrt ([#10500](https://github.com/librenms/librenms/pull/10500)) - [arrmo](https://github.com/arrmo)
* Fixed missing FW and Serials in Dlink ([#10481](https://github.com/librenms/librenms/pull/10481)) - [hanserasmus](https://github.com/hanserasmus)
* Added definition for Cisco SB SG250X ([#10472](https://github.com/librenms/librenms/pull/10472)) - [PipoCanaja](https://github.com/PipoCanaja)
* Extended RecoveryOS Definition ([#10475](https://github.com/librenms/librenms/pull/10475)) - [h-barnhart](https://github.com/h-barnhart)

#### Webui
* Show a hint that trend line exists ([#10573](https://github.com/librenms/librenms/pull/10573)) - [murrant](https://github.com/murrant)
* Convert About page to Laravel ([#10551](https://github.com/librenms/librenms/pull/10551)) - [Jellyfrog](https://github.com/Jellyfrog)
* Sort Devices and Groups in Alert Rules 'map to' droplist ([#10530](https://github.com/librenms/librenms/pull/10530)) - [SourceDoctor](https://github.com/SourceDoctor)
* Fixed menu links that used to redirect to # ([#10540](https://github.com/librenms/librenms/pull/10540)) - [Jellyfrog](https://github.com/Jellyfrog)
* Fix public status location ([#10526](https://github.com/librenms/librenms/pull/10526)) - [murrant](https://github.com/murrant)
* Fix Syslog widget ([#10516](https://github.com/librenms/librenms/pull/10516)) - [murrant](https://github.com/murrant)
* Add device group filter to widgets ([#9692](https://github.com/librenms/librenms/pull/9692)) - [Jellyfrog](https://github.com/Jellyfrog)
* Nfdump support for with NFSen ([#10376](https://github.com/librenms/librenms/pull/10376)) - [VVelox](https://github.com/VVelox)
* Laravel 5.8 and updated dependencies ([#10489](https://github.com/librenms/librenms/pull/10489)) - [murrant](https://github.com/murrant)
* Add an option to hide Location column in Alerts widget ([#10482](https://github.com/librenms/librenms/pull/10482)) - [dsgagi](https://github.com/dsgagi)
* Update services.inc.php ([#10486](https://github.com/librenms/librenms/pull/10486)) - [SniperVegeta](https://github.com/SniperVegeta)
* Check PHP version first ([#10473](https://github.com/librenms/librenms/pull/10473)) - [murrant](https://github.com/murrant)
* Add resources/views/menu/ to .gitignore ([#10479](https://github.com/librenms/librenms/pull/10479)) - [frankmcc](https://github.com/frankmcc)

#### Graphs
* Fix some graphs having the wrong timeframe ([#10554](https://github.com/librenms/librenms/pull/10554)) - [murrant](https://github.com/murrant)
* Added Cisco-voice IP graphs ([#10538](https://github.com/librenms/librenms/pull/10538)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fixed unauth graphs not working ([#10483](https://github.com/librenms/librenms/pull/10483)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Api
* Ports API: Workaround for ifNames with slashes ([#10502](https://github.com/librenms/librenms/pull/10502)) - [murrant](https://github.com/murrant)
* Allowed device_ids as INT or as STRING ([#10536](https://github.com/librenms/librenms/pull/10536)) - [TvL2386](https://github.com/TvL2386)
* Move API routing to Laravel ([#10457](https://github.com/librenms/librenms/pull/10457)) - [murrant](https://github.com/murrant)

#### Alerting
* Include alert ID in alert templates ([#10552](https://github.com/librenms/librenms/pull/10552)) - [SniperVegeta](https://github.com/SniperVegeta)

#### Discovery
* Allow num_oid to use OCTET STRING indexes ([#10410](https://github.com/librenms/librenms/pull/10410)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Bug
* Fix testing fping output when the LibreNMS user doesn't have a valid … ([#10567](https://github.com/librenms/librenms/pull/10567)) - [BrianSidebotham](https://github.com/BrianSidebotham)
* Fix Graylog level -1 display ([#10560](https://github.com/librenms/librenms/pull/10560)) - [murrant](https://github.com/murrant)
* Use PHP sys_temp_dir by default ([#10428](https://github.com/librenms/librenms/pull/10428)) - [deajan](https://github.com/deajan)
* Fix ipv6_network_id query for `null` context_name ([#10544](https://github.com/librenms/librenms/pull/10544)) - [garysteers](https://github.com/garysteers)
* Fixed Incorrect device match in Graylog ([#10501](https://github.com/librenms/librenms/pull/10501)) - [rsys-dev](https://github.com/rsys-dev)
* Fix .env with number symbols ([#10497](https://github.com/librenms/librenms/pull/10497)) - [murrant](https://github.com/murrant)

#### Documentation
* Update FAQ.md ([#10513](https://github.com/librenms/librenms/pull/10513)) - [hanserasmus](https://github.com/hanserasmus)
* Update Applications.md for mysql ([#10549](https://github.com/librenms/librenms/pull/10549)) - [opalivan](https://github.com/opalivan)
* Fixes the invalid json of the example curl statement ([#10537](https://github.com/librenms/librenms/pull/10537)) - [TvL2386](https://github.com/TvL2386)
* Update Installation-CentOS-7-Apache.md ([#10504](https://github.com/librenms/librenms/pull/10504)) - [hanserasmus](https://github.com/hanserasmus)
* Typo fix, minor textual changes in support docs ([#10499](https://github.com/librenms/librenms/pull/10499)) - [voipmeister](https://github.com/voipmeister)
* Fix installation instructions for Ubuntu-1804 ([#10488](https://github.com/librenms/librenms/pull/10488)) - [jvit](https://github.com/jvit)
* Oxidized - Recover a configuration of a disabled/removed device ([#10469](https://github.com/librenms/librenms/pull/10469)) - [FTBZ](https://github.com/FTBZ)
* Missing an I from Input ([#10474](https://github.com/librenms/librenms/pull/10474)) - [Munzy](https://github.com/Munzy)

#### Translation
* Update zh-TW.json for about page ([#10558](https://github.com/librenms/librenms/pull/10558)) - [jasoncheng7115](https://github.com/jasoncheng7115)

#### Misc
* Add inbit and outbit rate to auxiliary datastores. ([#10512](https://github.com/librenms/librenms/pull/10512)) - [SteFletcher](https://github.com/SteFletcher)
* Automatically cleanup plugin-table from removed plugins ([#10533](https://github.com/librenms/librenms/pull/10533)) - [SourceDoctor](https://github.com/SourceDoctor)
* Added Graylog to device overview and log level filter mechanism ([#10509](https://github.com/librenms/librenms/pull/10509)) - [rsys-dev](https://github.com/rsys-dev)
* Fix alert log status ([#10524](https://github.com/librenms/librenms/pull/10524)) - [SniperVegeta](https://github.com/SniperVegeta)
* Remove legacy auth usage of $_SESSION ([#10491](https://github.com/librenms/librenms/pull/10491)) - [murrant](https://github.com/murrant)
* Smart -power on hour -  view fix ([#10466](https://github.com/librenms/librenms/pull/10466)) - [SourceDoctor](https://github.com/SourceDoctor)
* Watchguard Fireware is FirewareOS in oxidized ([#10494](https://github.com/librenms/librenms/pull/10494)) - [deajan](https://github.com/deajan)


## 1.54
*(2019-07-28)*

A big thank you to the following 32 contributors this last month:

  - murrant (7)
  - CirnoT (6)
  - PipoCanaja (5)
  - jozefrebjak (5)
  - h-barnhart (2)
  - vitalisator (2)
  - VVelox (2)
  - N-Mi (2)
  - rsys-dev (2)
  - arrmo (2)
  - jasoncheng7115 (1)
  - xorrkaz (1)
  - tgregory86 (1)
  - sthen (1)
  - steffann (1)
  - sajanp (1)
  - SourceDoctor (1)
  - ospfbgp (1)
  - awarre (1)
  - filippog (1)
  - Serazio (1)
  - bergroth (1)
  - rmedlyn (1)
  - bestlong (1)
  - djamp42 (1)
  - VirTechSystems (1)
  - MinePlugins (1)
  - ig0rb (1)
  - ifred16 (1)
  - martijn-schmidt (1)
  - Derova (1)
  - abuzze (1)

#### Feature
* MPLS Services ([#10421](https://github.com/librenms/librenms/pull/10421)) - [vitalisator](https://github.com/vitalisator)
* Graylog entry matching device if source is not hostname or primary ip ([#10458](https://github.com/librenms/librenms/pull/10458)) - [rsys-dev](https://github.com/rsys-dev)
* Allow filtering of getUserlist LDAP function ([#10399](https://github.com/librenms/librenms/pull/10399)) - [ifred16](https://github.com/ifred16)

#### Breaking Change
* Refactor Api transport to use Guzzle (and new variables syntax) ([#10070](https://github.com/librenms/librenms/pull/10070)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Security
* Enable CSRF protection ([#10447](https://github.com/librenms/librenms/pull/10447)) - [murrant](https://github.com/murrant)

#### Device
* Add OpenWrt OS support (discovery, poller) ([#10454](https://github.com/librenms/librenms/pull/10454)) - [arrmo](https://github.com/arrmo)
* Temperature limits from MIB ([#10326](https://github.com/librenms/librenms/pull/10326)) - [martijn-schmidt](https://github.com/martijn-schmidt)
* FS.net pdu ([#10424](https://github.com/librenms/librenms/pull/10424)) - [ig0rb](https://github.com/ig0rb)
* Added Support For Teltonika RUT2XX Devices ([#10358](https://github.com/librenms/librenms/pull/10358)) - [jozefrebjak](https://github.com/jozefrebjak)
* Fix NetAgent II battery voltage ([#10427](https://github.com/librenms/librenms/pull/10427)) - [CirnoT](https://github.com/CirnoT)
* Add phase2 name to fortigate IPSEC sensor. ([#10423](https://github.com/librenms/librenms/pull/10423)) - [VirTechSystems](https://github.com/VirTechSystems)
* Add svg image for Roku ([#10448](https://github.com/librenms/librenms/pull/10448)) - [arrmo](https://github.com/arrmo)
* Added VRP SFPs thresholds and map entPhysical to ifIndexes ([#10363](https://github.com/librenms/librenms/pull/10363)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added F5 ssl tps, global server/client connection rate and active connections ([#9883](https://github.com/librenms/librenms/pull/9883)) - [Serazio](https://github.com/Serazio)
* Updating RAPID-CITY mib for Extreme VSP ([#10406](https://github.com/librenms/librenms/pull/10406)) - [ospfbgp](https://github.com/ospfbgp)
* Update $rancid_map For Mikrotik ([#10426](https://github.com/librenms/librenms/pull/10426)) - [sajanp](https://github.com/sajanp)
* New Sensor Data, Nokia Subscriber Statistics ([#10422](https://github.com/librenms/librenms/pull/10422)) - [vitalisator](https://github.com/vitalisator)
* Added detection for ZTE zxdsl devices ([#10344](https://github.com/librenms/librenms/pull/10344)) - [rsys-dev](https://github.com/rsys-dev)
* Added Support for Unitrends Backup ([#10411](https://github.com/librenms/librenms/pull/10411)) - [jozefrebjak](https://github.com/jozefrebjak)
* Added VPN sensors for Fortinet Fortigate ([#10384](https://github.com/librenms/librenms/pull/10384)) - [jozefrebjak](https://github.com/jozefrebjak)

#### Webui
* Fix Google maps lat/lon query string ([#10463](https://github.com/librenms/librenms/pull/10463)) - [filippog](https://github.com/filippog)
* Fix 2fa enable ([#10462](https://github.com/librenms/librenms/pull/10462)) - [murrant](https://github.com/murrant)
* Add more detail to webgui alerts ([#10388](https://github.com/librenms/librenms/pull/10388)) - [djamp42](https://github.com/djamp42)
* Fix Nan value broken maps network graph ([#10408](https://github.com/librenms/librenms/pull/10408)) - [bestlong](https://github.com/bestlong)
* Fix structure of network_map_legend default ([#10429](https://github.com/librenms/librenms/pull/10429)) - [rmedlyn](https://github.com/rmedlyn)
* Smoking outgoing graphs fix ([#10415](https://github.com/librenms/librenms/pull/10415)) - [steffann](https://github.com/steffann)
* Set Service Ignore and Disabled in UI ([#10334](https://github.com/librenms/librenms/pull/10334)) - [h-barnhart](https://github.com/h-barnhart)
* Replace color indicator near uptime counter with colored text and change color of status indicator to black on disabled devices instead of gray (matches availablity map with show ignored/disabled enabled) ([#10372](https://github.com/librenms/librenms/pull/10372)) - [CirnoT](https://github.com/CirnoT)
* Ignore disabled components in component widget ([#10369](https://github.com/librenms/librenms/pull/10369)) - [abuzze](https://github.com/abuzze)

#### Alerting
* Fix alert and template test scripts ([#10464](https://github.com/librenms/librenms/pull/10464)) - [murrant](https://github.com/murrant)
* Alert Subsys to OOP and SNMPTraps trigger Alert Rules ([#9765](https://github.com/librenms/librenms/pull/9765)) - [h-barnhart](https://github.com/h-barnhart)
* Add support for using Markdown for the Ciscospark transport ([#10442](https://github.com/librenms/librenms/pull/10442)) - [xorrkaz](https://github.com/xorrkaz)

#### Billing
* Don't display INF% for percentage of used transfer when billing is CDR ([#10446](https://github.com/librenms/librenms/pull/10446)) - [CirnoT](https://github.com/CirnoT)
* Properly format 95th CDR as SI Mbps in billing ([#10444](https://github.com/librenms/librenms/pull/10444)) - [CirnoT](https://github.com/CirnoT)
* Fix missing background on progress-bar for 95th bills ([#10443](https://github.com/librenms/librenms/pull/10443)) - [CirnoT](https://github.com/CirnoT)

#### Discovery
* Added support for DGD and BER on newer infinera-groove FW ([#10435](https://github.com/librenms/librenms/pull/10435)) - [bergroth](https://github.com/bergroth)
* Ensure that sysName is trimmed on discovery ([#10434](https://github.com/librenms/librenms/pull/10434)) - [CirnoT](https://github.com/CirnoT)
* Added skip_values operator and documentation ([#10419](https://github.com/librenms/librenms/pull/10419)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Bug
* Typo in Spelling prevented new services from being added. ([#10420](https://github.com/librenms/librenms/pull/10420)) - [tgregory86](https://github.com/tgregory86)
* Fix doc test after changelog split ([#10412](https://github.com/librenms/librenms/pull/10412)) - [N-Mi](https://github.com/N-Mi)

#### Documentation
* Fix docs build ([#10461](https://github.com/librenms/librenms/pull/10461)) - [murrant](https://github.com/murrant)
* Fixed broken links ([#10459](https://github.com/librenms/librenms/pull/10459)) - [Derova](https://github.com/Derova)
* Transport API - Doc for placeholders ([#10416](https://github.com/librenms/librenms/pull/10416)) - [PipoCanaja](https://github.com/PipoCanaja)
* Mistake in url API ([#10455](https://github.com/librenms/librenms/pull/10455)) - [MinePlugins](https://github.com/MinePlugins)
* More md linting ([#10371](https://github.com/librenms/librenms/pull/10371)) - [VVelox](https://github.com/VVelox)
* Fixed typo: Administartor ([#10437](https://github.com/librenms/librenms/pull/10437)) - [awarre](https://github.com/awarre)
* Mdadm application documentation ([#10430](https://github.com/librenms/librenms/pull/10430)) - [SourceDoctor](https://github.com/SourceDoctor)
* Make Applications.md more lint happy and add a section on sudo at the top ([#10367](https://github.com/librenms/librenms/pull/10367)) - [VVelox](https://github.com/VVelox)
* Split 2017 and 2018 changelogs ([#10404](https://github.com/librenms/librenms/pull/10404)) - [N-Mi](https://github.com/N-Mi)
* Update Smokeping.md ([#10407](https://github.com/librenms/librenms/pull/10407)) - [jozefrebjak](https://github.com/jozefrebjak)
* Update Portactivity Applications.md ([#10394](https://github.com/librenms/librenms/pull/10394)) - [jozefrebjak](https://github.com/jozefrebjak)

#### Translation
* Make Disabled/Shutdown to be translatable ([#10398](https://github.com/librenms/librenms/pull/10398)) - [jasoncheng7115](https://github.com/jasoncheng7115)

#### Misc
* Avoid unnecessary net-snmp long options for version info ([#10405](https://github.com/librenms/librenms/pull/10405)) - [sthen](https://github.com/sthen)


## 1.53
*(2019-07-01)*

A big thank you to the following 28 contributors this last month:

  - murrant (32)
  - jozefrebjak (4)
  - SourceDoctor (4)
  - jasoncheng7115 (4)
  - PipoCanaja (4)
  - ckforum (3)
  - VVelox (3)
  - vitalisator (3)
  - djamp42 (3)
  - martijn-schmidt (3)
  - llarian0 (2)
  - JoshWeepie (2)
  - kkrumm1 (2)
  - TheGreatDoc (1)
  - funzoneq (1)
  - CirnoT (1)
  - TheMysteriousX (1)
  - Marlinc (1)
  - daniviga (1)
  - rkislov (1)
  - StackOverBuffer (1)
  - janyksteenbeek (1)
  - p4k8 (1)
  - Cormoran96 (1)
  - tvcabomz (1)
  - SniperVegeta (1)
  - N-Mi (1)
  - mjducharme (1)

#### Feature
* Allow sysName to be specified in lnms device:add for ping only ([#10381](https://github.com/librenms/librenms/pull/10381)) - [murrant](https://github.com/murrant)
* Rewritten device groups (including static) ([#10295](https://github.com/librenms/librenms/pull/10295)) - [murrant](https://github.com/murrant)
* Add MPLS Support ([#10263](https://github.com/librenms/librenms/pull/10263)) - [vitalisator](https://github.com/vitalisator)
* Added aggregate config option to Billing 95th percentile calculations ([#10202](https://github.com/librenms/librenms/pull/10202)) - [llarian0](https://github.com/llarian0)

#### Device
* Create sensors.php and wireless.php for zh-TW ([#10368](https://github.com/librenms/librenms/pull/10368)) - [jasoncheng7115](https://github.com/jasoncheng7115)
* Nokia bgp admin status fix ([#10370](https://github.com/librenms/librenms/pull/10370)) - [vitalisator](https://github.com/vitalisator)
* WIP - Added VRP SFPs thresholds and map entPhysical to ifIndexes ([#10355](https://github.com/librenms/librenms/pull/10355)) - [PipoCanaja](https://github.com/PipoCanaja)
* Aruba IAP: Fix Radio State Sensor ([#10335](https://github.com/librenms/librenms/pull/10335)) - [kkrumm1](https://github.com/kkrumm1)
* Add raisecom os version, hardware and serial data ([#10336](https://github.com/librenms/librenms/pull/10336)) - [vitalisator](https://github.com/vitalisator)
* Add power sensor for eaton ups ([#10306](https://github.com/librenms/librenms/pull/10306)) - [StackOverBuffer](https://github.com/StackOverBuffer)
* Support for Fibernet XMUX4+ ([#10331](https://github.com/librenms/librenms/pull/10331)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Extend the Dell drac module to report CMC status and sensors ([#10310](https://github.com/librenms/librenms/pull/10310)) - [daniviga](https://github.com/daniviga)
* Cisco UCOS Version and Feature Fix ([#10307](https://github.com/librenms/librenms/pull/10307)) - [djamp42](https://github.com/djamp42)
* Add Ipoman power consumption support ([#10244](https://github.com/librenms/librenms/pull/10244)) - [Marlinc](https://github.com/Marlinc)
* CIMC Version Fix ([#10284](https://github.com/librenms/librenms/pull/10284)) - [djamp42](https://github.com/djamp42)
* Add a 'session' sensor for PanOS, SRX5800 Flow Accounting ([#8857](https://github.com/librenms/librenms/pull/8857)) - [TheMysteriousX](https://github.com/TheMysteriousX)
* Convert OS mrv-od to yaml, discover more sensors, discover entity-physical ([#10266](https://github.com/librenms/librenms/pull/10266)) - [martijn-schmidt](https://github.com/martijn-schmidt)
* Icotera support for 6400 and 6800 series. ([#9755](https://github.com/librenms/librenms/pull/9755)) - [funzoneq](https://github.com/funzoneq)
* Added detection and sensors for Huawei SMU device ([#10267](https://github.com/librenms/librenms/pull/10267)) - [jozefrebjak](https://github.com/jozefrebjak)

#### Webui
* Use sensor labels for overview/inventory pages, refactor some html-page related code ([#10287](https://github.com/librenms/librenms/pull/10287)) - [martijn-schmidt](https://github.com/martijn-schmidt)
* Add custom title to alert widget ([#10373](https://github.com/librenms/librenms/pull/10373)) - [djamp42](https://github.com/djamp42)
* Add 2 css class graph - minigraph for bg color and other ([#10318](https://github.com/librenms/librenms/pull/10318)) - [ckforum](https://github.com/ckforum)
* Improve UI of filter menu ([#10348](https://github.com/librenms/librenms/pull/10348)) - [JoshWeepie](https://github.com/JoshWeepie)
* Sort Device Applications in Optionbar alphabetic ([#10324](https://github.com/librenms/librenms/pull/10324)) - [SourceDoctor](https://github.com/SourceDoctor)
* Update VMWare guest IDs ([#10338](https://github.com/librenms/librenms/pull/10338)) - [murrant](https://github.com/murrant)
* Fix language select for new languages ([#10323](https://github.com/librenms/librenms/pull/10323)) - [murrant](https://github.com/murrant)
* Fix smokeping graphs ([#10317](https://github.com/librenms/librenms/pull/10317)) - [murrant](https://github.com/murrant)
* Change \<h2\>\</h1\> ? by span and class like the other ([#10305](https://github.com/librenms/librenms/pull/10305)) - [ckforum](https://github.com/ckforum)
* Add overlib link css class for changing background color - Update Url.php ([#10300](https://github.com/librenms/librenms/pull/10300)) - [ckforum](https://github.com/ckforum)
* WEB UI Changed color of Non Unicast Packets ([#10289](https://github.com/librenms/librenms/pull/10289)) - [jozefrebjak](https://github.com/jozefrebjak)
* Restore vminfo menu ([#10303](https://github.com/librenms/librenms/pull/10303)) - [murrant](https://github.com/murrant)
* Fix global service count showing on device overview ([#10301](https://github.com/librenms/librenms/pull/10301)) - [murrant](https://github.com/murrant)
* User Management: use url helpers ([#10288](https://github.com/librenms/librenms/pull/10288)) - [murrant](https://github.com/murrant)
* Only allow mysql auth type to add users ([#10283](https://github.com/librenms/librenms/pull/10283)) - [murrant](https://github.com/murrant)
* Don't show warning when ignored device is online (pingable) ([#10286](https://github.com/librenms/librenms/pull/10286)) - [CirnoT](https://github.com/CirnoT)
* Store language select name in translation files ([#10272](https://github.com/librenms/librenms/pull/10272)) - [murrant](https://github.com/murrant)
* Fixed Quick Graphs bug w/ Aggregate 95th code ([#10269](https://github.com/librenms/librenms/pull/10269)) - [llarian0](https://github.com/llarian0)

#### Graphs
* Fix atuc chan curr tx rate/atur chan curr tx rate ([#10383](https://github.com/librenms/librenms/pull/10383)) - [SniperVegeta](https://github.com/SniperVegeta)
* Support relative time for graphs again ([#10359](https://github.com/librenms/librenms/pull/10359)) - [murrant](https://github.com/murrant)
* Mdadm rrd graph fix ([#10312](https://github.com/librenms/librenms/pull/10312)) - [SourceDoctor](https://github.com/SourceDoctor)
* Removed broken POE graphing code ([#10188](https://github.com/librenms/librenms/pull/10188)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Applications
* Sort arrays before storing them in a component ([#10329](https://github.com/librenms/librenms/pull/10329)) - [VVelox](https://github.com/VVelox)
* Smart application database update fix ([#10378](https://github.com/librenms/librenms/pull/10378)) - [SourceDoctor](https://github.com/SourceDoctor)
* Fix an issue where the order may be random when adding values to the UPS-APC RRD ([#10375](https://github.com/librenms/librenms/pull/10375)) - [VVelox](https://github.com/VVelox)
* Enhance smart to show power_on_hours also ([#10261](https://github.com/librenms/librenms/pull/10261)) - [SourceDoctor](https://github.com/SourceDoctor)

#### Alerting
* Fix Dummy alert transport ([#10379](https://github.com/librenms/librenms/pull/10379)) - [murrant](https://github.com/murrant)
* Don't include time macros in field list ([#10299](https://github.com/librenms/librenms/pull/10299)) - [murrant](https://github.com/murrant)

#### Security
* Sanitize graph input ([#10276](https://github.com/librenms/librenms/pull/10276)) - [murrant](https://github.com/murrant)
* Sanitize report name in pdf.php ([#10270](https://github.com/librenms/librenms/pull/10270)) - [murrant](https://github.com/murrant)

#### Bug
* Fix broken updates ([#10380](https://github.com/librenms/librenms/pull/10380)) - [murrant](https://github.com/murrant)
* Fix mysql bug in cisco-sla module ([#10357](https://github.com/librenms/librenms/pull/10357)) - [tvcabomz](https://github.com/tvcabomz)
* Check correct path for config in the installer ([#10333](https://github.com/librenms/librenms/pull/10333)) - [janyksteenbeek](https://github.com/janyksteenbeek)
* Fix hytera_h2f bug ([#10281](https://github.com/librenms/librenms/pull/10281)) - [murrant](https://github.com/murrant)
* Fix for RouterOS LLDP discovery ([#10265](https://github.com/librenms/librenms/pull/10265)) - [mjducharme](https://github.com/mjducharme)

#### Documentation
* Fix markdown in Changelog ([#10387](https://github.com/librenms/librenms/pull/10387)) - [N-Mi](https://github.com/N-Mi)
* Update and fix link for Migrating from Observium ([#10377](https://github.com/librenms/librenms/pull/10377)) - [kkrumm1](https://github.com/kkrumm1)
* Go through making lots of the docs more lint happy ([#10342](https://github.com/librenms/librenms/pull/10342)) - [VVelox](https://github.com/VVelox)
* Remove guessed limits for some health sensors, documentation for sensor classes ([#10327](https://github.com/librenms/librenms/pull/10327)) - [martijn-schmidt](https://github.com/martijn-schmidt)
* Fix multiple typos in SNMP Trap doc ([#10343](https://github.com/librenms/librenms/pull/10343)) - [JoshWeepie](https://github.com/JoshWeepie)
* Split install steps into git clone and composer install ([#10249](https://github.com/librenms/librenms/pull/10249)) - [murrant](https://github.com/murrant)
* Example SNMP Trap handler class ([#10311](https://github.com/librenms/librenms/pull/10311)) - [jozefrebjak](https://github.com/jozefrebjak)
* Added configs of huawei devices into syslog.md ([#10309](https://github.com/librenms/librenms/pull/10309)) - [jozefrebjak](https://github.com/jozefrebjak)

#### Translation
* Update zh-TW ([#10391](https://github.com/librenms/librenms/pull/10391)) - [jasoncheng7115](https://github.com/jasoncheng7115)
* Update zh-TW ([#10361](https://github.com/librenms/librenms/pull/10361)) - [jasoncheng7115](https://github.com/jasoncheng7115)
* French language support ([#10277](https://github.com/librenms/librenms/pull/10277)) - [Cormoran96](https://github.com/Cormoran96)
* Traditional Chinese language support ([#10178](https://github.com/librenms/librenms/pull/10178)) - [jasoncheng7115](https://github.com/jasoncheng7115)
* Russian language update ([#10319](https://github.com/librenms/librenms/pull/10319)) - [rkislov](https://github.com/rkislov)
* Ukrainian language support ([#10328](https://github.com/librenms/librenms/pull/10328)) - [p4k8](https://github.com/p4k8)
* Enable menu translation ([#10298](https://github.com/librenms/librenms/pull/10298)) - [murrant](https://github.com/murrant)

#### Misc
* Use Config class instead of global ([#10339](https://github.com/librenms/librenms/pull/10339)) - [murrant](https://github.com/murrant)
* Update dependencies ([#10325](https://github.com/librenms/librenms/pull/10325)) - [murrant](https://github.com/murrant)
* Warn maintenance tasks are disabled ([#10273](https://github.com/librenms/librenms/pull/10273)) - [murrant](https://github.com/murrant)
* Dispatcher Service: Remove duplicate polling complete message ([#10290](https://github.com/librenms/librenms/pull/10290)) - [murrant](https://github.com/murrant)


## 1.52
*(2019-05-27)*

A big thank you to the following 28 contributors this last month:

  - murrant (30)
  - CirnoT (13)
  - h-barnhart (4)
  - PipoCanaja (4)
  - twilley (3)
  - pobradovic08 (3)
  - corsoblaster (2)
  - spencerbutler (2)
  - kmpanilla (2)
  - jozefrebjak (2)
  - slashdoom (2)
  - marvink87 (1)
  - davidmnelson (1)
  - Anthony25 (1)
  - supertylerc (1)
  - rkislov (1)
  - LeoWinterDE (1)
  - sparkkraps (1)
  - vitalisator (1)
  - SourceDoctor (1)
  - dsgagi (1)
  - VirTechSystems (1)
  - efelon (1)
  - deesel (1)
  - thomseddon (1)
  - mjducharme (1)
  - daniviga (1)
  - JoshWeepie (1)

#### Feature
* User configurable locale (language) ([#10204](https://github.com/librenms/librenms/pull/10204)) - [murrant](https://github.com/murrant)
* LLDP Discovery by IP ([#10130](https://github.com/librenms/librenms/pull/10130)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added additional generic SNMP trap handlers ([#10177](https://github.com/librenms/librenms/pull/10177)) - [CirnoT](https://github.com/CirnoT)

#### Device
* Fix power consumption detection on Dell servers ([#10250](https://github.com/librenms/librenms/pull/10250)) - [daniviga](https://github.com/daniviga)
* Updated OS (ftd) for Cisco FirePOWER devices ([#10046](https://github.com/librenms/librenms/pull/10046)) - [spencerbutler](https://github.com/spencerbutler)
* Update to planetos for ISG-* models ([#10152](https://github.com/librenms/librenms/pull/10152)) - [kmpanilla](https://github.com/kmpanilla)
* ArubaOS - fix client count polling, add ap count polling. ([#10231](https://github.com/librenms/librenms/pull/10231)) - [twilley](https://github.com/twilley)
* Added support for East iStars UPS (os: istars) ([#10041](https://github.com/librenms/librenms/pull/10041)) - [spencerbutler](https://github.com/spencerbutler)
* Collect Appliance serial number from Sophos device ([#10210](https://github.com/librenms/librenms/pull/10210)) - [corsoblaster](https://github.com/corsoblaster)
* Fix Siklu Version/Serial ([#10235](https://github.com/librenms/librenms/pull/10235)) - [kmpanilla](https://github.com/kmpanilla)
* Added Wireless discovery to Huawei Vrp ([#9516](https://github.com/librenms/librenms/pull/9516)) - [PipoCanaja](https://github.com/PipoCanaja)
* Add support for ZyNOS MGS switches ([#10234](https://github.com/librenms/librenms/pull/10234)) - [vitalisator](https://github.com/vitalisator)
* Initial detection for huawei gpon MDU ([#9733](https://github.com/librenms/librenms/pull/9733)) - [jozefrebjak](https://github.com/jozefrebjak)
* Replace Cyberoam with Sophos (icon and logo) ([#10213](https://github.com/librenms/librenms/pull/10213)) - [corsoblaster](https://github.com/corsoblaster)
* NEW OS Aruba Instant ([#9954](https://github.com/librenms/librenms/pull/9954)) - [twilley](https://github.com/twilley)
* Fix Raspberry Pi frequency, voltage and state sensors discovery ([#10176](https://github.com/librenms/librenms/pull/10176)) - [CirnoT](https://github.com/CirnoT)
* Add support for PoE state sensor on Mikrotik devices ([#10201](https://github.com/librenms/librenms/pull/10201)) - [CirnoT](https://github.com/CirnoT)
* Fortigate sessions sensors ([#10183](https://github.com/librenms/librenms/pull/10183)) - [marvink87](https://github.com/marvink87)
* Modified adva port label to use ifname ([#10165](https://github.com/librenms/librenms/pull/10165)) - [h-barnhart](https://github.com/h-barnhart)
* Fixed Avtech discovery ([#10163](https://github.com/librenms/librenms/pull/10163)) - [murrant](https://github.com/murrant)
* Added support for APC PDU outlet state sensors ([#10166](https://github.com/librenms/librenms/pull/10166)) - [CirnoT](https://github.com/CirnoT)
* Add support for Transition NIDs ([#9729](https://github.com/librenms/librenms/pull/9729)) - [JoshWeepie](https://github.com/JoshWeepie)

#### Webui
* Fix can't set poller group on ping only device ([#10260](https://github.com/librenms/librenms/pull/10260)) - [murrant](https://github.com/murrant)
* Netscaler vsvr - fixed wrong table colspan ([#10246](https://github.com/librenms/librenms/pull/10246)) - [pobradovic08](https://github.com/pobradovic08)
* Fix device groups showing multiple times ([#10247](https://github.com/librenms/librenms/pull/10247)) - [murrant](https://github.com/murrant)
* Use Laravel url helpers to improve functionality without dns name ([#10227](https://github.com/librenms/librenms/pull/10227)) - [murrant](https://github.com/murrant)
* Netscaler vservers table update ([#10103](https://github.com/librenms/librenms/pull/10103)) - [pobradovic08](https://github.com/pobradovic08)
* Try to make port counts match user expectations ([#10230](https://github.com/librenms/librenms/pull/10230)) - [murrant](https://github.com/murrant)
* Disable browser autocomplete dropdown for global search ([#10233](https://github.com/librenms/librenms/pull/10233)) - [murrant](https://github.com/murrant)
* Order device group menu by name ([#10216](https://github.com/librenms/librenms/pull/10216)) - [VirTechSystems](https://github.com/VirTechSystems)
* OSPF display improvements ([#10206](https://github.com/librenms/librenms/pull/10206)) - [dsgagi](https://github.com/dsgagi)
* Better services graphing support ([#10185](https://github.com/librenms/librenms/pull/10185)) - [CirnoT](https://github.com/CirnoT)
* Fix state sensors on device health page showing always as OK (green) ([#10200](https://github.com/librenms/librenms/pull/10200)) - [CirnoT](https://github.com/CirnoT)
* Replace legacy menu with new Blade generated one ([#10173](https://github.com/librenms/librenms/pull/10173)) - [murrant](https://github.com/murrant)
* Move container to page in blade tempates ([#10195](https://github.com/librenms/librenms/pull/10195)) - [murrant](https://github.com/murrant)
* Realtime graph handle snmp server caching ([#10113](https://github.com/librenms/librenms/pull/10113)) - [murrant](https://github.com/murrant)
* Specify graph format from GET param ([#10118](https://github.com/librenms/librenms/pull/10118)) - [Anthony25](https://github.com/Anthony25)
* Fix sensors on health table always showing as good ([#10171](https://github.com/librenms/librenms/pull/10171)) - [CirnoT](https://github.com/CirnoT)
* Russian language support ([#10137](https://github.com/librenms/librenms/pull/10137)) - [rkislov](https://github.com/rkislov)
* Handle edge case in graph view for Munin plugins ([#10127](https://github.com/librenms/librenms/pull/10127)) - [CirnoT](https://github.com/CirnoT)

#### Snmp Traps
* Juniper BGP4 Trap Handler update values in DB ([#10180](https://github.com/librenms/librenms/pull/10180)) - [h-barnhart](https://github.com/h-barnhart)
* SNMP Trap Handlers for Ruckus Wireless ([#10175](https://github.com/librenms/librenms/pull/10175)) - [h-barnhart](https://github.com/h-barnhart)
* Update bridge STP trap handlers to log events under stp type ([#10192](https://github.com/librenms/librenms/pull/10192)) - [CirnoT](https://github.com/CirnoT)
* Juniper SNMP Trap Handlers ([#10136](https://github.com/librenms/librenms/pull/10136)) - [h-barnhart](https://github.com/h-barnhart)
* Add failed user login trap for Netgear switches ([#10161](https://github.com/librenms/librenms/pull/10161)) - [CirnoT](https://github.com/CirnoT)
* Support for APC PDU Outlet traps ([#10162](https://github.com/librenms/librenms/pull/10162)) - [CirnoT](https://github.com/CirnoT)

#### Api
* Fix location missing from API device list ([#10215](https://github.com/librenms/librenms/pull/10215)) - [murrant](https://github.com/murrant)
* API Fix error when no fdb are found ([#10125](https://github.com/librenms/librenms/pull/10125)) - [murrant](https://github.com/murrant)
* Update legacy_api_v0.php ([#10209](https://github.com/librenms/librenms/pull/10209)) - [sparkkraps](https://github.com/sparkkraps)

#### Alerting
* Fix alert follow up for custom queries ([#10253](https://github.com/librenms/librenms/pull/10253)) - [thomseddon](https://github.com/thomseddon)
* SMS Eagle reduce chances of user mis-configuration ([#10223](https://github.com/librenms/librenms/pull/10223)) - [murrant](https://github.com/murrant)
* Cast alert ID to string for PD API ([#10186](https://github.com/librenms/librenms/pull/10186)) - [supertylerc](https://github.com/supertylerc)

#### Bug
* Fixed Cisco MAC accounting discovery, polling and HTML templates. ([#10158](https://github.com/librenms/librenms/pull/10158)) - [deesel](https://github.com/deesel)
* Prevent fail2ban from filling eventlog on every poll ([#10225](https://github.com/librenms/librenms/pull/10225)) - [efelon](https://github.com/efelon)
* Ignore empty IPv4 addresses in discovery on buggy devices ([#10198](https://github.com/librenms/librenms/pull/10198)) - [CirnoT](https://github.com/CirnoT)
* Netstats-udp, tcp and ip rrd's not updating ([#10197](https://github.com/librenms/librenms/pull/10197)) - [slashdoom](https://github.com/slashdoom)
* Fix MySQL error were prepared statement contains too many placeholders ([#10153](https://github.com/librenms/librenms/pull/10153)) - [davidmnelson](https://github.com/davidmnelson)
* Fix debug message ([#10189](https://github.com/librenms/librenms/pull/10189)) - [murrant](https://github.com/murrant)

#### Documentation
* Fix incorrect file path in custom-graph.md ([#10238](https://github.com/librenms/librenms/pull/10238)) - [jozefrebjak](https://github.com/jozefrebjak)
* Instructions for logstash ([#10252](https://github.com/librenms/librenms/pull/10252)) - [mjducharme](https://github.com/mjducharme)
* Fix broken links and anchors ([#10194](https://github.com/librenms/librenms/pull/10194)) - [pobradovic08](https://github.com/pobradovic08)
* Fix alerting docs redirect ([#10193](https://github.com/librenms/librenms/pull/10193)) - [murrant](https://github.com/murrant)
* Add 'software-properties-common' ([#10092](https://github.com/librenms/librenms/pull/10092)) - [LeoWinterDE](https://github.com/LeoWinterDE)


## 1.52
*(2019-05-27)*

A big thank you to the following 28 contributors this last month:

  - murrant (30)
  - CirnoT (13)
  - PipoCanaja (4)
  - h-barnhart (4)
  - twilley (3)
  - pobradovic08 (3)
  - spencerbutler (2)
  - kmpanilla (2)
  - slashdoom (2)
  - jozefrebjak (2)
  - corsoblaster (2)
  - marvink87 (1)
  - davidmnelson (1)
  - daniviga (1)
  - supertylerc (1)
  - Anthony25 (1)
  - rkislov (1)
  - LeoWinterDE (1)
  - sparkkraps (1)
  - efelon (1)
  - SourceDoctor (1)
  - dsgagi (1)
  - VirTechSystems (1)
  - vitalisator (1)
  - deesel (1)
  - thomseddon (1)
  - mjducharme (1)
  - JoshWeepie (1)

#### Feature
* User configurable locale (language) ([#10204](https://github.com/librenms/librenms/pull/10204)) - [murrant](https://github.com/murrant)
* LLDP Discovery by IP ([#10130](https://github.com/librenms/librenms/pull/10130)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added additional generic SNMP trap handlers ([#10177](https://github.com/librenms/librenms/pull/10177)) - [CirnoT](https://github.com/CirnoT)

#### Device
* Fix power consumption detection on Dell servers ([#10250](https://github.com/librenms/librenms/pull/10250)) - [daniviga](https://github.com/daniviga)
* Updated OS (ftd) for Cisco FirePOWER devices ([#10046](https://github.com/librenms/librenms/pull/10046)) - [spencerbutler](https://github.com/spencerbutler)
* Update to planetos for ISG-* models ([#10152](https://github.com/librenms/librenms/pull/10152)) - [kmpanilla](https://github.com/kmpanilla)
* ArubaOS - fix client count polling, add ap count polling. ([#10231](https://github.com/librenms/librenms/pull/10231)) - [twilley](https://github.com/twilley)
* Added support for East iStars UPS (os: istars) ([#10041](https://github.com/librenms/librenms/pull/10041)) - [spencerbutler](https://github.com/spencerbutler)
* Collect Appliance serial number from Sophos device ([#10210](https://github.com/librenms/librenms/pull/10210)) - [corsoblaster](https://github.com/corsoblaster)
* Fix Siklu Version/Serial ([#10235](https://github.com/librenms/librenms/pull/10235)) - [kmpanilla](https://github.com/kmpanilla)
* Added Wireless discovery to Huawei Vrp ([#9516](https://github.com/librenms/librenms/pull/9516)) - [PipoCanaja](https://github.com/PipoCanaja)
* Add support for ZyNOS MGS switches ([#10234](https://github.com/librenms/librenms/pull/10234)) - [vitalisator](https://github.com/vitalisator)
* Initial detection for huawei gpon MDU ([#9733](https://github.com/librenms/librenms/pull/9733)) - [jozefrebjak](https://github.com/jozefrebjak)
* NEW OS Aruba Instant ([#9954](https://github.com/librenms/librenms/pull/9954)) - [twilley](https://github.com/twilley)
* Fix Raspberry Pi frequency, voltage and state sensors discovery ([#10176](https://github.com/librenms/librenms/pull/10176)) - [CirnoT](https://github.com/CirnoT)
* Add support for PoE state sensor on Mikrotik devices ([#10201](https://github.com/librenms/librenms/pull/10201)) - [CirnoT](https://github.com/CirnoT)
* Fortigate sessions sensors ([#10183](https://github.com/librenms/librenms/pull/10183)) - [marvink87](https://github.com/marvink87)
* Fixed Avtech discovery ([#10163](https://github.com/librenms/librenms/pull/10163)) - [murrant](https://github.com/murrant)
* Added support for APC PDU outlet state sensors ([#10166](https://github.com/librenms/librenms/pull/10166)) - [CirnoT](https://github.com/CirnoT)
* Add support for Transition NIDs ([#9729](https://github.com/librenms/librenms/pull/9729)) - [JoshWeepie](https://github.com/JoshWeepie)

#### Webui
* Fix can't set poller group on ping only device ([#10260](https://github.com/librenms/librenms/pull/10260)) - [murrant](https://github.com/murrant)
* Netscaler vsvr - fixed wrong table colspan ([#10246](https://github.com/librenms/librenms/pull/10246)) - [pobradovic08](https://github.com/pobradovic08)
* Fix device groups showing multiple times ([#10247](https://github.com/librenms/librenms/pull/10247)) - [murrant](https://github.com/murrant)
* Use Laravel url helpers to improve functionality without dns name ([#10227](https://github.com/librenms/librenms/pull/10227)) - [murrant](https://github.com/murrant)
* Netscaler vservers table update ([#10103](https://github.com/librenms/librenms/pull/10103)) - [pobradovic08](https://github.com/pobradovic08)
* Try to make port counts match user expectations ([#10230](https://github.com/librenms/librenms/pull/10230)) - [murrant](https://github.com/murrant)
* Disable browser autocomplete dropdown for global search ([#10233](https://github.com/librenms/librenms/pull/10233)) - [murrant](https://github.com/murrant)
* Order device group menu by name ([#10216](https://github.com/librenms/librenms/pull/10216)) - [VirTechSystems](https://github.com/VirTechSystems)
* OSPF display improvements ([#10206](https://github.com/librenms/librenms/pull/10206)) - [dsgagi](https://github.com/dsgagi)
* Fix state sensors on device health page showing always as OK (green) ([#10200](https://github.com/librenms/librenms/pull/10200)) - [CirnoT](https://github.com/CirnoT)
* Replace legacy menu with new Blade generated one ([#10173](https://github.com/librenms/librenms/pull/10173)) - [murrant](https://github.com/murrant)
* Move container to page in blade tempates ([#10195](https://github.com/librenms/librenms/pull/10195)) - [murrant](https://github.com/murrant)
* Realtime graph handle snmp server caching ([#10113](https://github.com/librenms/librenms/pull/10113)) - [murrant](https://github.com/murrant)
* Specify graph format from GET param ([#10118](https://github.com/librenms/librenms/pull/10118)) - [Anthony25](https://github.com/Anthony25)
* Fix sensors on health table always showing as good ([#10171](https://github.com/librenms/librenms/pull/10171)) - [CirnoT](https://github.com/CirnoT)
* Russian language support ([#10137](https://github.com/librenms/librenms/pull/10137)) - [rkislov](https://github.com/rkislov)
* Handle edge case in graph view for Munin plugins ([#10127](https://github.com/librenms/librenms/pull/10127)) - [CirnoT](https://github.com/CirnoT)

#### Snmp Traps
* Add failed user login trap for Netgear switches ([#10161](https://github.com/librenms/librenms/pull/10161)) - [CirnoT](https://github.com/CirnoT)
* Support for APC PDU Outlet traps ([#10162](https://github.com/librenms/librenms/pull/10162)) - [CirnoT](https://github.com/CirnoT)

#### Api
* Fix location missing from API device list ([#10215](https://github.com/librenms/librenms/pull/10215)) - [murrant](https://github.com/murrant)
* API Fix error when no fdb are found ([#10125](https://github.com/librenms/librenms/pull/10125)) - [murrant](https://github.com/murrant)
* Update legacy_api_v0.php ([#10209](https://github.com/librenms/librenms/pull/10209)) - [sparkkraps](https://github.com/sparkkraps)

#### Alerting
* SMS Eagle reduce chances of user mis-configuration ([#10223](https://github.com/librenms/librenms/pull/10223)) - [murrant](https://github.com/murrant)

#### Bug
* Fixed Cisco MAC accounting discovery, polling and HTML templates. ([#10158](https://github.com/librenms/librenms/pull/10158)) - [deesel](https://github.com/deesel)
* Ignore empty IPv4 addresses in discovery on buggy devices ([#10198](https://github.com/librenms/librenms/pull/10198)) - [CirnoT](https://github.com/CirnoT)
* Netstats-udp, tcp and ip rrd's not updating ([#10197](https://github.com/librenms/librenms/pull/10197)) - [slashdoom](https://github.com/slashdoom)
* Fix MySQL error were prepared statement contains too many placeholders ([#10153](https://github.com/librenms/librenms/pull/10153)) - [davidmnelson](https://github.com/davidmnelson)

#### Documentation
* Fix broken links and anchors ([#10194](https://github.com/librenms/librenms/pull/10194)) - [pobradovic08](https://github.com/pobradovic08)
* Fix alerting docs redirect ([#10193](https://github.com/librenms/librenms/pull/10193)) - [murrant](https://github.com/murrant)
* Add 'software-properties-common' ([#10092](https://github.com/librenms/librenms/pull/10092)) - [LeoWinterDE](https://github.com/LeoWinterDE)


## 1.51
*(2019-04-29)*

A big thank you to the following 29 contributors this last month:

  - murrant (19)
  - PipoCanaja (8)
  - CirnoT (7)
  - spencerbutler (5)
  - laf (4)
  - pobradovic08 (3)
  - TheGreatDoc (3)
  - h-barnhart (2)
  - twilley (2)
  - djamp42 (2)
  - smiles1969 (2)
  - VVelox (1)
  - kmpanilla (1)
  - martijn-schmidt (1)
  - petracvv (1)
  - cppmonkey (1)
  - tigerdjohnson (1)
  - Slushnas (1)
  - tim427 (1)
  - n0taz (1)
  - zombah (1)
  - andrewimeson (1)
  - tomarch (1)
  - mattie47 (1)
  - dmeiser (1)
  - neszt (1)
  - priiduonu (1)
  - vitalisator (1)
  - longchihang (1)

#### Device
* Serial number and more robust OS version for Netgear switches ([#10164](https://github.com/librenms/librenms/pull/10164)) - [CirnoT](https://github.com/CirnoT)
* Extended sensors for Timos devices ([#10160](https://github.com/librenms/librenms/pull/10160)) - [vitalisator](https://github.com/vitalisator)
* Added support for Zmtel greenpacket devices (os: zmtel) ([#10067](https://github.com/librenms/librenms/pull/10067)) - [spencerbutler](https://github.com/spencerbutler)
* Get and display the image patch version on Huawei VRP devices ([#10099](https://github.com/librenms/librenms/pull/10099)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added packetlight support ([#10131](https://github.com/librenms/librenms/pull/10131)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fortinet SNMP Trap Handlers ([#10148](https://github.com/librenms/librenms/pull/10148)) - [h-barnhart](https://github.com/h-barnhart)
* Adva SNMP Trap Handlers ([#10094](https://github.com/librenms/librenms/pull/10094)) - [h-barnhart](https://github.com/h-barnhart)
* Add PSU state to Netgear discovery definition ([#10150](https://github.com/librenms/librenms/pull/10150)) - [CirnoT](https://github.com/CirnoT)
* Add memory pool for Netgear switches ([#10146](https://github.com/librenms/librenms/pull/10146)) - [CirnoT](https://github.com/CirnoT)
* Updates to planetos.yaml for additional models ([#10149](https://github.com/librenms/librenms/pull/10149)) - [kmpanilla](https://github.com/kmpanilla)
* Add discovery ObjectID for Barracuda NGFW ([#10102](https://github.com/librenms/librenms/pull/10102)) - [pobradovic08](https://github.com/pobradovic08)
* Added support dellNet devices ([#10016](https://github.com/librenms/librenms/pull/10016)) - [spencerbutler](https://github.com/spencerbutler)
* Improved Linksys support, including POE ([#10075](https://github.com/librenms/librenms/pull/10075)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added Cisco Small business bootloader + HW version ([#10043](https://github.com/librenms/librenms/pull/10043)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added detection for ESW 5xx series of Cisco SB devices ([#10077](https://github.com/librenms/librenms/pull/10077)) - [laf](https://github.com/laf)
* Extended card support for adva_fsp150 family ([#10049](https://github.com/librenms/librenms/pull/10049)) - [PipoCanaja](https://github.com/PipoCanaja)
* Updated RegEx string for correct definitions for Proxmox 4.x nodes ([#10048](https://github.com/librenms/librenms/pull/10048)) - [n0taz](https://github.com/n0taz)
* Improve Huawei BGP polling + BGP webui & graphs patches ([#10010](https://github.com/librenms/librenms/pull/10010)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added support for Liebert PDUs ([#10062](https://github.com/librenms/librenms/pull/10062)) - [spencerbutler](https://github.com/spencerbutler)
* Added initial support for teltonika ([#10059](https://github.com/librenms/librenms/pull/10059)) - [tomarch](https://github.com/tomarch)
* Added support for TP-LINK T1600G-52TS ([#9983](https://github.com/librenms/librenms/pull/9983)) - [spencerbutler](https://github.com/spencerbutler)
* Fix aruba-controller polling ([#10071](https://github.com/librenms/librenms/pull/10071)) - [twilley](https://github.com/twilley)
* Added device WISI Tangram ([#10039](https://github.com/librenms/librenms/pull/10039)) - [djamp42](https://github.com/djamp42)
* Added PPPoE Sessions Graph for Mikrotik ([#10056](https://github.com/librenms/librenms/pull/10056)) - [neszt](https://github.com/neszt)
* Fix gw-eydfa detection ([#10052](https://github.com/librenms/librenms/pull/10052)) - [murrant](https://github.com/murrant)
* Added support for IONODES video encoders ([#10031](https://github.com/librenms/librenms/pull/10031)) - [priiduonu](https://github.com/priiduonu)
* Added support for DELLEMC-OS10-PRODUCTS-MIB (os: dell-os10) ([#10011](https://github.com/librenms/librenms/pull/10011)) - [spencerbutler](https://github.com/spencerbutler)

#### Bug
* Store IPv4 networks as network address and fix address search page showing networks not addresses ([#10144](https://github.com/librenms/librenms/pull/10144)) - [CirnoT](https://github.com/CirnoT)
* Fix filter by device and interface type on IP address search page ([#10143](https://github.com/librenms/librenms/pull/10143)) - [CirnoT](https://github.com/CirnoT)
* Fix services with scripts inheriting DS from previous service on detail view ([#10142](https://github.com/librenms/librenms/pull/10142)) - [CirnoT](https://github.com/CirnoT)
* Fix call to shortDisplayName on null in MuninPluginController ([#10126](https://github.com/librenms/librenms/pull/10126)) - [CirnoT](https://github.com/CirnoT)
* Fix install.php can't find config.php ([#10129](https://github.com/librenms/librenms/pull/10129)) - [murrant](https://github.com/murrant)
* Fix call to isUnderMaintenance() on null ([#10090](https://github.com/librenms/librenms/pull/10090)) - [murrant](https://github.com/murrant)
* Don't require db for config_to_json.php ([#10100](https://github.com/librenms/librenms/pull/10100)) - [murrant](https://github.com/murrant)
* Bug - Nasty user_func vs divisor-multiplier issue ([#10122](https://github.com/librenms/librenms/pull/10122)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix to display minimum values in uptime graphs. ([#10078](https://github.com/librenms/librenms/pull/10078)) - [Slushnas](https://github.com/Slushnas)
* Fix notification creation ([#10058](https://github.com/librenms/librenms/pull/10058)) - [murrant](https://github.com/murrant)
* Fixed fail2ban jails eventlog spam ([#10061](https://github.com/librenms/librenms/pull/10061)) - [murrant](https://github.com/murrant)

#### Webui
* Easily setting font colors for RRD graphs is now possible ([#10083](https://github.com/librenms/librenms/pull/10083)) - [VVelox](https://github.com/VVelox)
* New User Management ([#9348](https://github.com/librenms/librenms/pull/9348)) - [murrant](https://github.com/murrant)
* Display number of connections for ASA on over ([#10106](https://github.com/librenms/librenms/pull/10106)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix to display minimum values in uptime graphs. ([#10078](https://github.com/librenms/librenms/pull/10078)) - [Slushnas](https://github.com/Slushnas)
* Refactored Nvidia Application ([#10037](https://github.com/librenms/librenms/pull/10037)) - [tim427](https://github.com/tim427)
* Improve Huawei BGP polling + BGP webui & graphs patches ([#10010](https://github.com/librenms/librenms/pull/10010)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix notification creation ([#10058](https://github.com/librenms/librenms/pull/10058)) - [murrant](https://github.com/murrant)
* Add SysName to Oxidized view ([#10012](https://github.com/librenms/librenms/pull/10012)) - [smiles1969](https://github.com/smiles1969)

#### Documentation
* Updated Code-Structure.md ([#10156](https://github.com/librenms/librenms/pull/10156)) - [pobradovic08](https://github.com/pobradovic08)
* Fix formatting ([#10135](https://github.com/librenms/librenms/pull/10135)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Fix paths of custom graph examples in Custom-Graphs.md ([#10128](https://github.com/librenms/librenms/pull/10128)) - [pobradovic08](https://github.com/pobradovic08)
* Update Example-Hardware-Setup.md ([#10115](https://github.com/librenms/librenms/pull/10115)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Update Templates.md ([#10120](https://github.com/librenms/librenms/pull/10120)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Example Hardware - corrected markup ([#10117](https://github.com/librenms/librenms/pull/10117)) - [cppmonkey](https://github.com/cppmonkey)
* Minor word usage corrections ([#10073](https://github.com/librenms/librenms/pull/10073)) - [andrewimeson](https://github.com/andrewimeson)
* Update Smokeping.md ([#10064](https://github.com/librenms/librenms/pull/10064)) - [mattie47](https://github.com/mattie47)
* Update SNMP-Configuration-Examples ([#10063](https://github.com/librenms/librenms/pull/10063)) - [dmeiser](https://github.com/dmeiser)
* LibreNMS python service doc updates ([#10044](https://github.com/librenms/librenms/pull/10044)) - [murrant](https://github.com/murrant)

#### Api
* Allow Add_Device API to set sysName ([#10124](https://github.com/librenms/librenms/pull/10124)) - [djamp42](https://github.com/djamp42)
* Fix api *log date format ([#10133](https://github.com/librenms/librenms/pull/10133)) - [murrant](https://github.com/murrant)
* Fix arp api network query ([#10085](https://github.com/librenms/librenms/pull/10085)) - [murrant](https://github.com/murrant)
* Fixed a duplicate route name in the api ([#10082](https://github.com/librenms/librenms/pull/10082)) - [laf](https://github.com/laf)
* Add API call to list all ports FDB ([#10020](https://github.com/librenms/librenms/pull/10020)) - [zombah](https://github.com/zombah)
* Added slms => zhoneolt mapping for Oxidized model ([#10068](https://github.com/librenms/librenms/pull/10068)) - [laf](https://github.com/laf)

#### Alerting
* Relax validation for smseagle hostname ([#10141](https://github.com/librenms/librenms/pull/10141)) - [petracvv](https://github.com/petracvv)
* Removed legacy code from transports ([#10081](https://github.com/librenms/librenms/pull/10081)) - [laf](https://github.com/laf)

#### Security
* Fix unescaped variables in ajax_search.php ([#10088](https://github.com/librenms/librenms/pull/10088)) - [murrant](https://github.com/murrant)
* Security fix: unauthorized access ([#10091](https://github.com/librenms/librenms/pull/10091)) - [murrant](https://github.com/murrant)

#### Feature
* Update json error message to show how to debug. ([#9998](https://github.com/librenms/librenms/pull/9998)) - [murrant](https://github.com/murrant)


## 1.50
*(2019-03-31)*

A big thank you to the following 31 contributors this last month:

  - murrant (37)
  - PipoCanaja (26)
  - spencerbutler (6)
  - amigne (5)
  - vitalisator (4)
  - djamp42 (3)
  - cppmonkey (3)
  - TheGreatDoc (3)
  - nickhilliard (2)
  - llcoolkm (2)
  - JoshWeepie (1)
  - fjwcash (1)
  - VVelox (1)
  - sorano (1)
  - kkrumm1 (1)
  - rmedlyn (1)
  - florianbeer (1)
  - cliffalbert (1)
  - jozefrebjak (1)
  - zombah (1)
  - kiwibrew (1)
  - network-guy (1)
  - rmagomedov (1)
  - priiduonu (1)
  - ospfbgp (1)
  - jasoncheng7115 (1)
  - GitStoph (1)
  - shward (1)
  - koocotte (1)
  - dracmic (1)
  - sjtarik (1)

#### Feature
* Printer paper tray status and error states ([#9859](https://github.com/librenms/librenms/pull/9859)) - [sjtarik](https://github.com/sjtarik)
* Added support for custom storage warning percentage ([#9975](https://github.com/librenms/librenms/pull/9975)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Added support for ciscosb to gen_rancid.php (cisco-sb) ([#9940](https://github.com/librenms/librenms/pull/9940)) - [cliffalbert](https://github.com/cliffalbert)
* Access to "sub" index (when OID has multiple indexes) ([#9893](https://github.com/librenms/librenms/pull/9893)) - [PipoCanaja](https://github.com/PipoCanaja)
* Optional automatic sensor limits ([#9973](https://github.com/librenms/librenms/pull/9973)) - [amigne](https://github.com/amigne)

#### Bug
* Fix database validation for MySQL 8 ([#9923](https://github.com/librenms/librenms/pull/9923)) - [llcoolkm](https://github.com/llcoolkm)
* Fixed device missing from traps/new Log::event() ([#9963](https://github.com/librenms/librenms/pull/9963)) - [murrant](https://github.com/murrant)
* Fixed Cisco OTV (array)cast issue creating empty adj. ([#9968](https://github.com/librenms/librenms/pull/9968)) - [PipoCanaja](https://github.com/PipoCanaja)
* Improved support for Dantel Webmon ([#9977](https://github.com/librenms/librenms/pull/9977)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fixed inconsistent \<h3\> closed by \</div\> ([#9982](https://github.com/librenms/librenms/pull/9982)) - [amigne](https://github.com/amigne)
* Fixed install not connecting to DB ([#9984](https://github.com/librenms/librenms/pull/9984)) - [murrant](https://github.com/murrant)
* Fixed mysql table engine validation ([#9989](https://github.com/librenms/librenms/pull/9989)) - [murrant](https://github.com/murrant)
* Fixed device list down devices that have never been polled ([#9994](https://github.com/librenms/librenms/pull/9994)) - [murrant](https://github.com/murrant)
* Fixed world map when location has been deleted that a device still references ([#9997](https://github.com/librenms/librenms/pull/9997)) - [murrant](https://github.com/murrant)
* Fixed device group queries again ([#10000](https://github.com/librenms/librenms/pull/10000)) - [murrant](https://github.com/murrant)
* Fixed transport options when edited on Windows ([#10001](https://github.com/librenms/librenms/pull/10001)) - [murrant](https://github.com/murrant)
* Fixed issue with new permissions code ([#10004](https://github.com/librenms/librenms/pull/10004)) - [murrant](https://github.com/murrant)
* Fixed bill permissions ([#10005](https://github.com/librenms/librenms/pull/10005)) - [murrant](https://github.com/murrant)
* Fixed an issue with bills with no data ([#10009](https://github.com/librenms/librenms/pull/10009)) - [murrant](https://github.com/murrant)
* Fixed error when user doesn't exist ([#10023](https://github.com/librenms/librenms/pull/10023)) - [murrant](https://github.com/murrant)
* Top ports widget: Work around bad data in the database ([#10024](https://github.com/librenms/librenms/pull/10024)) - [murrant](https://github.com/murrant)
* Properly set the component information when polling ([#10017](https://github.com/librenms/librenms/pull/10017)) - [VVelox](https://github.com/VVelox)
* Removed an errant character in cambium definitions ([#9996](https://github.com/librenms/librenms/pull/9996)) - [spencerbutler](https://github.com/spencerbutler)
* Fixed cisco temperature limit on discovery ([#9985](https://github.com/librenms/librenms/pull/9985)) - [amigne](https://github.com/amigne)
* Patch fix sql error on gengroupsql ([#9929](https://github.com/librenms/librenms/pull/9929)) - [dracmic](https://github.com/dracmic)
* Work around issue with Weathermaps ([#10033](https://github.com/librenms/librenms/pull/10033)) - [murrant](https://github.com/murrant)
* Typo in routeros YAML discovery ([#9903](https://github.com/librenms/librenms/pull/9903)) - [PipoCanaja](https://github.com/PipoCanaja)
* Don't enable secure cookies when they won't work ([#9971](https://github.com/librenms/librenms/pull/9971)) - [murrant](https://github.com/murrant)
* Do not use $sensor[sensor_limit] if not available ([#9978](https://github.com/librenms/librenms/pull/9978)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix an issue that could block install ([#9958](https://github.com/librenms/librenms/pull/9958)) - [murrant](https://github.com/murrant)
* Handle missing fields a little more gracefully ([#9919](https://github.com/librenms/librenms/pull/9919)) - [murrant](https://github.com/murrant)
* Fix ldap/ad auth anon-bind ([#9905](https://github.com/librenms/librenms/pull/9905)) - [murrant](https://github.com/murrant)
* Replace misplaced nokia/OSPFV3-MIB with a newer version to right place ([#9907](https://github.com/librenms/librenms/pull/9907)) - [vitalisator](https://github.com/vitalisator)
* Fixes to composer_wrapper proxy handling ([#9819](https://github.com/librenms/librenms/pull/9819)) - [murrant](https://github.com/murrant)
* Allow admins to add/remove/create sticky notifications ([#9865](https://github.com/librenms/librenms/pull/9865)) - [cppmonkey](https://github.com/cppmonkey)

#### Device
* Improve VRP stack state discovery with one member only to avoid unnecessary alarms ([#9925](https://github.com/librenms/librenms/pull/9925)) - [PipoCanaja](https://github.com/PipoCanaja)
* Improved Riello UPS support with RFC 1628 support ([#9962](https://github.com/librenms/librenms/pull/9962)) - [PipoCanaja](https://github.com/PipoCanaja)
* Improved support for Dantel Webmon ([#9977](https://github.com/librenms/librenms/pull/9977)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added Arris Apex support ([#10006](https://github.com/librenms/librenms/pull/10006)) - [djamp42](https://github.com/djamp42)
* Added Panduit Eagle-I (was Sinetica) support ([#10014](https://github.com/librenms/librenms/pull/10014)) - [PipoCanaja](https://github.com/PipoCanaja)
* Eltek Valere: Group sensors by shelf ([#10040](https://github.com/librenms/librenms/pull/10040)) - [murrant](https://github.com/murrant)
* Added support for APC AP9810 zone contacts ([#9967](https://github.com/librenms/librenms/pull/9967)) - [cppmonkey](https://github.com/cppmonkey)
* Added support for HikVision-DS Cameras ([#9980](https://github.com/librenms/librenms/pull/9980)) - [spencerbutler](https://github.com/spencerbutler)
* Added support for EDFA ([#9912](https://github.com/librenms/librenms/pull/9912)) - [jozefrebjak](https://github.com/jozefrebjak)
* Added support for Orvaldi UPS ([#10021](https://github.com/librenms/librenms/pull/10021)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added support for Ruijie Networks ([#10026](https://github.com/librenms/librenms/pull/10026)) - [spencerbutler](https://github.com/spencerbutler)
* Extend support for all emerson products ([#10018](https://github.com/librenms/librenms/pull/10018)) - [PipoCanaja](https://github.com/PipoCanaja)
* New Device: ATS - Automatic Transfer Switch ([#9889](https://github.com/librenms/librenms/pull/9889)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Add Device - Cisco Sat Receivers ([#9899](https://github.com/librenms/librenms/pull/9899)) - [djamp42](https://github.com/djamp42)
* Add Device Arris DSR-4410MD Sat Receiver ([#9943](https://github.com/librenms/librenms/pull/9943)) - [djamp42](https://github.com/djamp42)
* Added Med(5m) and High(15m) Utilization sensors for Cambium  APs (os: pmp) ([#9995](https://github.com/librenms/librenms/pull/9995)) - [spencerbutler](https://github.com/spencerbutler)
* Grandstream basic support ([#9906](https://github.com/librenms/librenms/pull/9906)) - [PipoCanaja](https://github.com/PipoCanaja)
* Dell UPS enable rfc 1628 support ([#9961](https://github.com/librenms/librenms/pull/9961)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added support for Cisco Small Business WAP371-a-k9 ([#9974](https://github.com/librenms/librenms/pull/9974)) - [spencerbutler](https://github.com/spencerbutler)
* Dantel WebMon Device Support ([#9767](https://github.com/librenms/librenms/pull/9767)) - [network-guy](https://github.com/network-guy)
* Added new OS - sensatronics-em1 ([#9960](https://github.com/librenms/librenms/pull/9960)) - [spencerbutler](https://github.com/spencerbutler)
* Eaton pdu extension ([#9947](https://github.com/librenms/librenms/pull/9947)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix Aruba Instant wireless sensors ([#9936](https://github.com/librenms/librenms/pull/9936)) - [murrant](https://github.com/murrant)
* Added Ciena Waveserver ([#9930](https://github.com/librenms/librenms/pull/9930)) - [PipoCanaja](https://github.com/PipoCanaja)
* Add Junos VirtuallChassis ports polling ([#9879](https://github.com/librenms/librenms/pull/9879)) - [rmagomedov](https://github.com/rmagomedov)
* Add support for Moxa EDS-G512E-8PoE ([#9857](https://github.com/librenms/librenms/pull/9857)) - [priiduonu](https://github.com/priiduonu)
* Improved Infinera Groove discovery ([#9913](https://github.com/librenms/librenms/pull/9913)) - [nickhilliard](https://github.com/nickhilliard)
* Add support for power supply on Extreme BOSS switches ([#9898](https://github.com/librenms/librenms/pull/9898)) - [ospfbgp](https://github.com/ospfbgp)
* Add support for cirpack soft switch ([#9914](https://github.com/librenms/librenms/pull/9914)) - [vitalisator](https://github.com/vitalisator)
* Added VRP stack member and ports discovery ([#9891](https://github.com/librenms/librenms/pull/9891)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added Patton SmartNode OS discovery and polling ([#9901](https://github.com/librenms/librenms/pull/9901)) - [PipoCanaja](https://github.com/PipoCanaja)
* Meraki MS: add serial number ([#9768](https://github.com/librenms/librenms/pull/9768)) - [GitStoph](https://github.com/GitStoph)
* Add data scrubbing state to Synology RAID status ([#9661](https://github.com/librenms/librenms/pull/9661)) - [florianbeer](https://github.com/florianbeer)
* Add support for Infinera-Coriant Groove ([#9843](https://github.com/librenms/librenms/pull/9843)) - [nickhilliard](https://github.com/nickhilliard)

#### Webui
* Allowed more characters in graph legend for interface names ([#9926](https://github.com/librenms/librenms/pull/9926)) - [PipoCanaja](https://github.com/PipoCanaja)
* Corrected active_count for Alert icon color ([#9933](https://github.com/librenms/librenms/pull/9933)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fixed inconsistent \<h3\> closed by \</div\> ([#9982](https://github.com/librenms/librenms/pull/9982)) - [amigne](https://github.com/amigne)
* Fixed world map when location has been deleted that a device still references ([#9997](https://github.com/librenms/librenms/pull/9997)) - [murrant](https://github.com/murrant)
* Improved Health limits display ([#10007](https://github.com/librenms/librenms/pull/10007)) - [amigne](https://github.com/amigne)
* Added Panduit Eagle-I (was Sinetica) support ([#10014](https://github.com/librenms/librenms/pull/10014)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fixed missing pipe in ports page menu ([#10025](https://github.com/librenms/librenms/pull/10025)) - [JoshWeepie](https://github.com/JoshWeepie)
* Added location to alert hostname tooltip ([#9991](https://github.com/librenms/librenms/pull/9991)) - [rmedlyn](https://github.com/rmedlyn)
* Beautify port health ([#9981](https://github.com/librenms/librenms/pull/9981)) - [amigne](https://github.com/amigne)
* Added a blue theme ([#9970](https://github.com/librenms/librenms/pull/9970)) - [PipoCanaja](https://github.com/PipoCanaja)
* Display Up/Down time in Device List ([#9951](https://github.com/librenms/librenms/pull/9951)) - [PipoCanaja](https://github.com/PipoCanaja)
* Add Alert-transports to Laravel menu blade ([#9946](https://github.com/librenms/librenms/pull/9946)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix graphs for ASA announcing all interfaces in type l2vlan (by default filtered) ([#9849](https://github.com/librenms/librenms/pull/9849)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix widgets page with MySQL 8 ([#9922](https://github.com/librenms/librenms/pull/9922)) - [llcoolkm](https://github.com/llcoolkm)
* Fixed sysName can't display because newline character ([#9921](https://github.com/librenms/librenms/pull/9921)) - [jasoncheng7115](https://github.com/jasoncheng7115)
* Allow admins to add/remove/create sticky notifications ([#9865](https://github.com/librenms/librenms/pull/9865)) - [cppmonkey](https://github.com/cppmonkey)

#### Alerting
* Added HTML transport example for ms teams ([#9969](https://github.com/librenms/librenms/pull/9969)) - [sorano](https://github.com/sorano)
* Fixed device group queries again ([#10000](https://github.com/librenms/librenms/pull/10000)) - [murrant](https://github.com/murrant)
* Fixed transport options when edited on Windows ([#10001](https://github.com/librenms/librenms/pull/10001)) - [murrant](https://github.com/murrant)
* Update documentation to reflect matching behaviour ([#9955](https://github.com/librenms/librenms/pull/9955)) - [kiwibrew](https://github.com/kiwibrew)

#### Documentation
* Added HTML transport example for ms teams ([#9969](https://github.com/librenms/librenms/pull/9969)) - [sorano](https://github.com/sorano)
* Fixed path in Smokeping conf file ([#10045](https://github.com/librenms/librenms/pull/10045)) - [fjwcash](https://github.com/fjwcash)
* Update Fast-Ping-Check.md ([#10022](https://github.com/librenms/librenms/pull/10022)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Update documentation to reflect matching behaviour ([#9955](https://github.com/librenms/librenms/pull/9955)) - [kiwibrew](https://github.com/kiwibrew)
* Update Getting-Started.md ([#9976](https://github.com/librenms/librenms/pull/9976)) - [PipoCanaja](https://github.com/PipoCanaja)
* Documentation for setting a development environment ([#9944](https://github.com/librenms/librenms/pull/9944)) - [murrant](https://github.com/murrant)
* Add new template syntax into the FAQ, pointing to the documentation ([#9942](https://github.com/librenms/librenms/pull/9942)) - [PipoCanaja](https://github.com/PipoCanaja)
* Add Debian instruction ([#9788](https://github.com/librenms/librenms/pull/9788)) - [koocotte](https://github.com/koocotte)
* Update Web UI debug FAQ ([#9816](https://github.com/librenms/librenms/pull/9816)) - [murrant](https://github.com/murrant)

#### Security
* Update dependencies ([#10002](https://github.com/librenms/librenms/pull/10002)) - [murrant](https://github.com/murrant)
* Prevent credentials from being leaked in backtrace in some instances ([#9817](https://github.com/librenms/librenms/pull/9817)) - [murrant](https://github.com/murrant)

#### Api
* Added resources/sensors api call to list all sensors ([#9837](https://github.com/librenms/librenms/pull/9837)) - [zombah](https://github.com/zombah)


## 1.49
*(2019-03-03)*

A big thank you to the following 36 contributors this last month:

  - murrant (30)
  - PipoCanaja (8)
  - TheGreatDoc (4)
  - cppmonkey (4)
  - SirMaple (3)
  - vitalisator (3)
  - Rosiak (2)
  - ipptac (2)
  - jozefrebjak (2)
  - djamp42 (2)
  - laf (2)
  - angryp (2)
  - crcro (2)
  - githubuserx (1)
  - TylerSweet (1)
  - aylham (1)
  - pobradovic08 (1)
  - felici (1)
  - ospfbgp (1)
  - Cormoran96 (1)
  - Anthony25 (1)
  - hlmtre (1)
  - kkrumm1 (1)
  - zombah (1)
  - TakeMeNL (1)
  - tharbakim (1)
  - mhzgh (1)
  - fake-name (1)
  - paraselene92 (1)
  - mbwall (1)
  - InsaneSplash (1)
  - sjtarik (1)
  - CoMMyz (1)
  - martijn-schmidt (1)
  - esundberg (1)
  - dsmfool (1)

#### Documentation
* Updated JumpCloud authentication example ([#9722](https://github.com/librenms/librenms/pull/9722)) - [dsmfool](https://github.com/dsmfool)
* Additional info for Postgres application ([#9791](https://github.com/librenms/librenms/pull/9791)) - [SirMaple](https://github.com/SirMaple)
* Update Example-Hardware-Setup.md ([#9897](https://github.com/librenms/librenms/pull/9897)) - [cppmonkey](https://github.com/cppmonkey)
* Fix link missing parenthesis ([#9895](https://github.com/librenms/librenms/pull/9895)) - [githubuserx](https://github.com/githubuserx)
* Added new install to example hardware setup ([#9872](https://github.com/librenms/librenms/pull/9872)) - [SirMaple](https://github.com/SirMaple)
* Clarification in server migration procedure ([#9848](https://github.com/librenms/librenms/pull/9848)) - [hlmtre](https://github.com/hlmtre)
* Update the bug report link in README.md ([#9850](https://github.com/librenms/librenms/pull/9850)) - [kkrumm1](https://github.com/kkrumm1)
* Remove extra semicolon from documentation. ([#9833](https://github.com/librenms/librenms/pull/9833)) - [tharbakim](https://github.com/tharbakim)
* Change minimum PHP version in install docs ([#9820](https://github.com/librenms/librenms/pull/9820)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Install docs, note proxy config ([#9720](https://github.com/librenms/librenms/pull/9720)) - [mhzgh](https://github.com/mhzgh)
* Fix Smokeping setup instructions so they actually work ([#9731](https://github.com/librenms/librenms/pull/9731)) - [fake-name](https://github.com/fake-name)
* Fix a link in support document ([#9808](https://github.com/librenms/librenms/pull/9808)) - [paraselene92](https://github.com/paraselene92)
* Update Poller Support.md ([#9769](https://github.com/librenms/librenms/pull/9769)) - [TheGreatDoc](https://github.com/TheGreatDoc)

#### Device
* Ruckus Wireless updates (ZD/SZ/Unleashed/Hotzone) ([#9727](https://github.com/librenms/librenms/pull/9727)) - [djamp42](https://github.com/djamp42)
* Fix Arista interface bias current divisor ([#9728](https://github.com/librenms/librenms/pull/9728)) - [Rosiak](https://github.com/Rosiak)
* Added power and fan sensors to VRP ([#9838](https://github.com/librenms/librenms/pull/9838)) - [jozefrebjak](https://github.com/jozefrebjak)
* [fix] edgeswitch v1.9 os detection ([#9868](https://github.com/librenms/librenms/pull/9868)) - [crcro](https://github.com/crcro)
* Add support for sagemcom ([#9835](https://github.com/librenms/librenms/pull/9835)) - [vitalisator](https://github.com/vitalisator)
* Add fan description to hwEntityFanState ([#9863](https://github.com/librenms/librenms/pull/9863)) - [PipoCanaja](https://github.com/PipoCanaja)
* [feat] edgeos hardware info ([#9867](https://github.com/librenms/librenms/pull/9867)) - [crcro](https://github.com/crcro)
* Added support for Alpha Comp@s ([#9871](https://github.com/librenms/librenms/pull/9871)) - [cppmonkey](https://github.com/cppmonkey)
* Discovery rcChasPowerSupplyOperStatus for Extreme/Avaya voss.inc.php stop working ([#9878](https://github.com/librenms/librenms/pull/9878)) - [ospfbgp](https://github.com/ospfbgp)
* Added Perle OS Support for IOLAN SCS ([#9866](https://github.com/librenms/librenms/pull/9866)) - [esundberg](https://github.com/esundberg)
* Netscaler SDWAN appliance - Serial# + Version and state sensors ([#9834](https://github.com/librenms/librenms/pull/9834)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added support for Protelevision DVB-T Transmitter ([#9648](https://github.com/librenms/librenms/pull/9648)) - [jozefrebjak](https://github.com/jozefrebjak)
* Netgear m5300 health sensors ([#9744](https://github.com/librenms/librenms/pull/9744)) - [cppmonkey](https://github.com/cppmonkey)
* Additional TPLink JetStream mem/cpu support ([#9829](https://github.com/librenms/librenms/pull/9829)) - [TakeMeNL](https://github.com/TakeMeNL)
* MAIPU MyPowerOS: CPU, Memory, expanded detection ([#9825](https://github.com/librenms/librenms/pull/9825)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Fix Junos CPU Discovery ([#9467](https://github.com/librenms/librenms/pull/9467)) - [Rosiak](https://github.com/Rosiak)
* Add support for Nokia ISAM ([#9793](https://github.com/librenms/librenms/pull/9793)) - [vitalisator](https://github.com/vitalisator)
* Updating pfSense Logo ([#9828](https://github.com/librenms/librenms/pull/9828)) - [SirMaple](https://github.com/SirMaple)
* Expand Cyberpower OS detection ([#9802](https://github.com/librenms/librenms/pull/9802)) - [murrant](https://github.com/murrant)
* Add osmc icon ([#9810](https://github.com/librenms/librenms/pull/9810)) - [murrant](https://github.com/murrant)
* Workaround of bad SNMP implementation in EDS device. ([#9801](https://github.com/librenms/librenms/pull/9801)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added Virtual Chassis Member Role Sensor ([#9783](https://github.com/librenms/librenms/pull/9783)) - [ipptac](https://github.com/ipptac)
* FS.COM (Fiberstore) 'GBN' and 'SWITCH' devices support ([#9734](https://github.com/librenms/librenms/pull/9734)) - [PipoCanaja](https://github.com/PipoCanaja)
* Support for DKT Comega FTTx devices ([#9732](https://github.com/librenms/librenms/pull/9732)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added support for EDS 1Wire devices ([#9740](https://github.com/librenms/librenms/pull/9740)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix regression in VC hardware detection for JunOS ([#9772](https://github.com/librenms/librenms/pull/9772)) - [martijn-schmidt](https://github.com/martijn-schmidt)
* New Device: Bluecat Networks appliances ([#9758](https://github.com/librenms/librenms/pull/9758)) - [ipptac](https://github.com/ipptac)

#### Alerting
* Fix Arista interface bias current divisor ([#9728](https://github.com/librenms/librenms/pull/9728)) - [Rosiak](https://github.com/Rosiak)
* LibreNMS/Alert/Transport/Elasticsearch - Send timestamp with timezone ([#9757](https://github.com/librenms/librenms/pull/9757)) - [pobradovic08](https://github.com/pobradovic08)
* Canopsis transport ([#9795](https://github.com/librenms/librenms/pull/9795)) - [aylham](https://github.com/aylham)
* Alertmanager fix 2 ([#9860](https://github.com/librenms/librenms/pull/9860)) - [angryp](https://github.com/angryp)
* Update Mattermost transport with configurable author_name ([#9759](https://github.com/librenms/librenms/pull/9759)) - [zombah](https://github.com/zombah)
* Restore alert template converter for a while longer ([#9845](https://github.com/librenms/librenms/pull/9845)) - [murrant](https://github.com/murrant)
* Removed legacy transports and templates code ([#9646](https://github.com/librenms/librenms/pull/9646)) - [laf](https://github.com/laf)
* Fix cisco compenent down macro ([#9805](https://github.com/librenms/librenms/pull/9805)) - [murrant](https://github.com/murrant)
* Fixed Alertmanager transport ([#9807](https://github.com/librenms/librenms/pull/9807)) - [angryp](https://github.com/angryp)
* Msteams consistent title ([#9774](https://github.com/librenms/librenms/pull/9774)) - [InsaneSplash](https://github.com/InsaneSplash)
* BGP Session down rule: add conditions for bgp admin status = stop ([#9773](https://github.com/librenms/librenms/pull/9773)) - [Cormoran96](https://github.com/Cormoran96)

#### Bug
* More 278 fixes mysql 5.7 does not like the variable names ([#9766](https://github.com/librenms/librenms/pull/9766)) - [murrant](https://github.com/murrant)
* Update to PHPMailer 6.0 (PHP 7.3 support) ([#9818](https://github.com/librenms/librenms/pull/9818)) - [felici](https://github.com/felici)
* Syslog hostname translation broken ([#9839](https://github.com/librenms/librenms/pull/9839)) - [TylerSweet](https://github.com/TylerSweet)
* Fix incorrect icon sometimes ([#9887](https://github.com/librenms/librenms/pull/9887)) - [murrant](https://github.com/murrant)
* Try to fix some of the Component code ([#9888](https://github.com/librenms/librenms/pull/9888)) - [murrant](https://github.com/murrant)
* Discovery rcChasPowerSupplyOperStatus for Extreme/Avaya voss.inc.php stop working ([#9878](https://github.com/librenms/librenms/pull/9878)) - [ospfbgp](https://github.com/ospfbgp)
* Misplaced mib file when adding FS.COM support ([#9886](https://github.com/librenms/librenms/pull/9886)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fixed validator for rrd folder permissions ([#9869](https://github.com/librenms/librenms/pull/9869)) - [cppmonkey](https://github.com/cppmonkey)
* Fix MyPowerOS mempools ([#9861](https://github.com/librenms/librenms/pull/9861)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Email should be optional in lnms user:add command ([#9841](https://github.com/librenms/librenms/pull/9841)) - [murrant](https://github.com/murrant)
* Fix logging too much ([#9824](https://github.com/librenms/librenms/pull/9824)) - [murrant](https://github.com/murrant)
* Fix for failed sql query during db dump ([#9815](https://github.com/librenms/librenms/pull/9815)) - [murrant](https://github.com/murrant)
* Fix cisco compenent down macro ([#9805](https://github.com/librenms/librenms/pull/9805)) - [murrant](https://github.com/murrant)
* Discard local changes to git based vendor packages ([#9813](https://github.com/librenms/librenms/pull/9813)) - [murrant](https://github.com/murrant)
* Fixed Alertmanager transport ([#9807](https://github.com/librenms/librenms/pull/9807)) - [angryp](https://github.com/angryp)
* Fix php version notification removal ([#9797](https://github.com/librenms/librenms/pull/9797)) - [murrant](https://github.com/murrant)
* Fix php version notification removal ([#9796](https://github.com/librenms/librenms/pull/9796)) - [murrant](https://github.com/murrant)
* Handle unexpected os when loading yaml ([#9790](https://github.com/librenms/librenms/pull/9790)) - [murrant](https://github.com/murrant)
* Fix alert log api ([#9792](https://github.com/librenms/librenms/pull/9792)) - [murrant](https://github.com/murrant)
* Fix schema validation and os def cache invalidation ([#9789](https://github.com/librenms/librenms/pull/9789)) - [murrant](https://github.com/murrant)
* Restore gitignore file contents ([#9784](https://github.com/librenms/librenms/pull/9784)) - [murrant](https://github.com/murrant)
* Port exists check in eventlog ([#9778](https://github.com/librenms/librenms/pull/9778)) - [CoMMyz](https://github.com/CoMMyz)
* Migration fixes ([#9776](https://github.com/librenms/librenms/pull/9776)) - [murrant](https://github.com/murrant)
* Prevent error with multiple proxmox ([#9770](https://github.com/librenms/librenms/pull/9770)) - [murrant](https://github.com/murrant)

#### Webui
* Fix debug display of rrdtool command ([#9846](https://github.com/librenms/librenms/pull/9846)) - [Anthony25](https://github.com/Anthony25)
* Ignore disabled ports in minigraph view ([#9737](https://github.com/librenms/librenms/pull/9737)) - [mbwall](https://github.com/mbwall)

#### Feature
* Improved Exception handling ([#9844](https://github.com/librenms/librenms/pull/9844)) - [murrant](https://github.com/murrant)
* FDB table with history capabilities ([#9804](https://github.com/librenms/librenms/pull/9804)) - [PipoCanaja](https://github.com/PipoCanaja)
* Php artisan serve and dusk testing ([#9422](https://github.com/librenms/librenms/pull/9422)) - [murrant](https://github.com/murrant)
* Lnms user:add command ([#9830](https://github.com/librenms/librenms/pull/9830)) - [murrant](https://github.com/murrant)

#### Api
* Fix alert log api ([#9792](https://github.com/librenms/librenms/pull/9792)) - [murrant](https://github.com/murrant)


## 1.49
*(2019-03-03)*

A big thank you to the following 36 contributors this last month:

  - murrant (30)
  - PipoCanaja (8)
  - cppmonkey (4)
  - TheGreatDoc (4)
  - SirMaple (3)
  - vitalisator (3)
  - crcro (2)
  - ipptac (2)
  - angryp (2)
  - jozefrebjak (2)
  - djamp42 (2)
  - laf (2)
  - Rosiak (2)
  - ospfbgp (1)
  - esundberg (1)
  - kkrumm1 (1)
  - Anthony25 (1)
  - hlmtre (1)
  - zombah (1)
  - TakeMeNL (1)
  - githubuserx (1)
  - tharbakim (1)
  - dsmfool (1)
  - felici (1)
  - mhzgh (1)
  - fake-name (1)
  - pobradovic08 (1)
  - paraselene92 (1)
  - aylham (1)
  - mbwall (1)
  - InsaneSplash (1)
  - sjtarik (1)
  - CoMMyz (1)
  - martijn-schmidt (1)
  - TylerSweet (1)
  - Cormoran96 (1)

#### Documentation
* Update Example-Hardware-Setup.md ([#9897](https://github.com/librenms/librenms/pull/9897)) - [cppmonkey](https://github.com/cppmonkey)
* Fix link missing parenthesis ([#9895](https://github.com/librenms/librenms/pull/9895)) - [githubuserx](https://github.com/githubuserx)
* Added new install to example hardware setup ([#9872](https://github.com/librenms/librenms/pull/9872)) - [SirMaple](https://github.com/SirMaple)
* Clarification in server migration procedure ([#9848](https://github.com/librenms/librenms/pull/9848)) - [hlmtre](https://github.com/hlmtre)
* Update the bug report link in README.md ([#9850](https://github.com/librenms/librenms/pull/9850)) - [kkrumm1](https://github.com/kkrumm1)
* Remove extra semicolon from documentation. ([#9833](https://github.com/librenms/librenms/pull/9833)) - [tharbakim](https://github.com/tharbakim)
* Change minimum PHP version in install docs ([#9820](https://github.com/librenms/librenms/pull/9820)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Install docs, note proxy config ([#9720](https://github.com/librenms/librenms/pull/9720)) - [mhzgh](https://github.com/mhzgh)
* Fix Smokeping setup instructions so they actually work ([#9731](https://github.com/librenms/librenms/pull/9731)) - [fake-name](https://github.com/fake-name)
* Fix a link in support document ([#9808](https://github.com/librenms/librenms/pull/9808)) - [paraselene92](https://github.com/paraselene92)
* Update Poller Support.md ([#9769](https://github.com/librenms/librenms/pull/9769)) - [TheGreatDoc](https://github.com/TheGreatDoc)

#### Bug
* Fix incorrect icon sometimes ([#9887](https://github.com/librenms/librenms/pull/9887)) - [murrant](https://github.com/murrant)
* Try to fix some of the Component code ([#9888](https://github.com/librenms/librenms/pull/9888)) - [murrant](https://github.com/murrant)
* Discovery rcChasPowerSupplyOperStatus for Extreme/Avaya voss.inc.php stop working ([#9878](https://github.com/librenms/librenms/pull/9878)) - [ospfbgp](https://github.com/ospfbgp)
* Misplaced mib file when adding FS.COM support ([#9886](https://github.com/librenms/librenms/pull/9886)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fixed validator for rrd folder permissions ([#9869](https://github.com/librenms/librenms/pull/9869)) - [cppmonkey](https://github.com/cppmonkey)
* Fix MyPowerOS mempools ([#9861](https://github.com/librenms/librenms/pull/9861)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Email should be optional in lnms user:add command ([#9841](https://github.com/librenms/librenms/pull/9841)) - [murrant](https://github.com/murrant)
* Fix logging too much ([#9824](https://github.com/librenms/librenms/pull/9824)) - [murrant](https://github.com/murrant)
* Fix for failed sql query during db dump ([#9815](https://github.com/librenms/librenms/pull/9815)) - [murrant](https://github.com/murrant)
* Fix cisco compenent down macro ([#9805](https://github.com/librenms/librenms/pull/9805)) - [murrant](https://github.com/murrant)
* Discard local changes to git based vendor packages ([#9813](https://github.com/librenms/librenms/pull/9813)) - [murrant](https://github.com/murrant)
* Fixed Alertmanager transport ([#9807](https://github.com/librenms/librenms/pull/9807)) - [angryp](https://github.com/angryp)
* Fix php version notification removal ([#9797](https://github.com/librenms/librenms/pull/9797)) - [murrant](https://github.com/murrant)
* Fix php version notification removal ([#9796](https://github.com/librenms/librenms/pull/9796)) - [murrant](https://github.com/murrant)
* Handle unexpected os when loading yaml ([#9790](https://github.com/librenms/librenms/pull/9790)) - [murrant](https://github.com/murrant)
* Fix alert log api ([#9792](https://github.com/librenms/librenms/pull/9792)) - [murrant](https://github.com/murrant)
* Fix schema validation and os def cache invalidation ([#9789](https://github.com/librenms/librenms/pull/9789)) - [murrant](https://github.com/murrant)
* Restore gitignore file contents ([#9784](https://github.com/librenms/librenms/pull/9784)) - [murrant](https://github.com/murrant)
* Port exists check in eventlog ([#9778](https://github.com/librenms/librenms/pull/9778)) - [CoMMyz](https://github.com/CoMMyz)
* Migration fixes ([#9776](https://github.com/librenms/librenms/pull/9776)) - [murrant](https://github.com/murrant)
* Prevent error with multiple proxmox ([#9770](https://github.com/librenms/librenms/pull/9770)) - [murrant](https://github.com/murrant)

#### Device
* Add support for sagemcom ([#9835](https://github.com/librenms/librenms/pull/9835)) - [vitalisator](https://github.com/vitalisator)
* Add fan description to hwEntityFanState ([#9863](https://github.com/librenms/librenms/pull/9863)) - [PipoCanaja](https://github.com/PipoCanaja)
* [feat] edgeos hardware info ([#9867](https://github.com/librenms/librenms/pull/9867)) - [crcro](https://github.com/crcro)
* Added support for Alpha Comp@s ([#9871](https://github.com/librenms/librenms/pull/9871)) - [cppmonkey](https://github.com/cppmonkey)
* Discovery rcChasPowerSupplyOperStatus for Extreme/Avaya voss.inc.php stop working ([#9878](https://github.com/librenms/librenms/pull/9878)) - [ospfbgp](https://github.com/ospfbgp)
* Added Perle OS Support for IOLAN SCS ([#9866](https://github.com/librenms/librenms/pull/9866)) - [esundberg](https://github.com/esundberg)
* Netscaler SDWAN appliance - Serial# + Version and state sensors ([#9834](https://github.com/librenms/librenms/pull/9834)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added support for Protelevision DVB-T Transmitter ([#9648](https://github.com/librenms/librenms/pull/9648)) - [jozefrebjak](https://github.com/jozefrebjak)
* Netgear m5300 health sensors ([#9744](https://github.com/librenms/librenms/pull/9744)) - [cppmonkey](https://github.com/cppmonkey)
* Additional TPLink JetStream mem/cpu support ([#9829](https://github.com/librenms/librenms/pull/9829)) - [TakeMeNL](https://github.com/TakeMeNL)
* MAIPU MyPowerOS: CPU, Memory, expanded detection ([#9825](https://github.com/librenms/librenms/pull/9825)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Fix Junos CPU Discovery ([#9467](https://github.com/librenms/librenms/pull/9467)) - [Rosiak](https://github.com/Rosiak)
* Add support for Nokia ISAM ([#9793](https://github.com/librenms/librenms/pull/9793)) - [vitalisator](https://github.com/vitalisator)
* Updating pfSense Logo ([#9828](https://github.com/librenms/librenms/pull/9828)) - [SirMaple](https://github.com/SirMaple)
* Expand Cyberpower OS detection ([#9802](https://github.com/librenms/librenms/pull/9802)) - [murrant](https://github.com/murrant)
* Add osmc icon ([#9810](https://github.com/librenms/librenms/pull/9810)) - [murrant](https://github.com/murrant)
* Workaround of bad SNMP implementation in EDS device. ([#9801](https://github.com/librenms/librenms/pull/9801)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added Virtual Chassis Member Role Sensor ([#9783](https://github.com/librenms/librenms/pull/9783)) - [ipptac](https://github.com/ipptac)
* FS.COM (Fiberstore) 'GBN' and 'SWITCH' devices support ([#9734](https://github.com/librenms/librenms/pull/9734)) - [PipoCanaja](https://github.com/PipoCanaja)
* Support for DKT Comega FTTx devices ([#9732](https://github.com/librenms/librenms/pull/9732)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added support for EDS 1Wire devices ([#9740](https://github.com/librenms/librenms/pull/9740)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix regression in VC hardware detection for JunOS ([#9772](https://github.com/librenms/librenms/pull/9772)) - [martijn-schmidt](https://github.com/martijn-schmidt)
* New Device: Bluecat Networks appliances ([#9758](https://github.com/librenms/librenms/pull/9758)) - [ipptac](https://github.com/ipptac)

#### Webui
* Fix debug display of rrdtool command ([#9846](https://github.com/librenms/librenms/pull/9846)) - [Anthony25](https://github.com/Anthony25)
* Ignore disabled ports in minigraph view ([#9737](https://github.com/librenms/librenms/pull/9737)) - [mbwall](https://github.com/mbwall)

#### Feature
* Improved Exception handling ([#9844](https://github.com/librenms/librenms/pull/9844)) - [murrant](https://github.com/murrant)
* FDB table with history capabilities ([#9804](https://github.com/librenms/librenms/pull/9804)) - [PipoCanaja](https://github.com/PipoCanaja)
* Php artisan serve and dusk testing ([#9422](https://github.com/librenms/librenms/pull/9422)) - [murrant](https://github.com/murrant)
* Lnms user:add command ([#9830](https://github.com/librenms/librenms/pull/9830)) - [murrant](https://github.com/murrant)

#### Alerting
* Update Mattermost transport with configurable author_name ([#9759](https://github.com/librenms/librenms/pull/9759)) - [zombah](https://github.com/zombah)
* Restore alert template converter for a while longer ([#9845](https://github.com/librenms/librenms/pull/9845)) - [murrant](https://github.com/murrant)
* Removed legacy transports and templates code ([#9646](https://github.com/librenms/librenms/pull/9646)) - [laf](https://github.com/laf)
* Fix cisco compenent down macro ([#9805](https://github.com/librenms/librenms/pull/9805)) - [murrant](https://github.com/murrant)
* Fixed Alertmanager transport ([#9807](https://github.com/librenms/librenms/pull/9807)) - [angryp](https://github.com/angryp)
* Msteams consistent title ([#9774](https://github.com/librenms/librenms/pull/9774)) - [InsaneSplash](https://github.com/InsaneSplash)
* BGP Session down rule: add conditions for bgp admin status = stop ([#9773](https://github.com/librenms/librenms/pull/9773)) - [Cormoran96](https://github.com/Cormoran96)

#### Api
* Fix alert log api ([#9792](https://github.com/librenms/librenms/pull/9792)) - [murrant](https://github.com/murrant)


## 1.48
*(2019-01-28)*

A big thank you to the following 31 contributors this last month:

  - murrant (59)
  - PipoCanaja (7)
  - vitalisator (3)
  - laf (3)
  - gpant (2)
  - Swashy (2)
  - JoshWeepie (2)
  - kkrumm1 (2)
  - djamp42 (2)
  - dharpster (1)
  - martijn-schmidt (1)
  - emestee (1)
  - marvink87 (1)
  - GitStoph (1)
  - sjtarik (1)
  - TheGreatDoc (1)
  - acl (1)
  - sanegaming (1)
  - evheros (1)
  - kiwibrew (1)
  - nova-2nd (1)
  - pheinrichs (1)
  - amtypaldos (1)
  - Kal42 (1)
  - angryp (1)
  - mikecentola (1)
  - jozefrebjak (1)
  - tim427 (1)
  - twelch24 (1)
  - zoc (1)
  - cppmonkey (1)

#### Alerting
* Added Mattermost Alert Transport ([#9749](https://github.com/librenms/librenms/pull/9749)) - [gpant](https://github.com/gpant)
* Added Alerta Alert Transport ([#9673](https://github.com/librenms/librenms/pull/9673)) - [GitStoph](https://github.com/GitStoph)
* Fix first column validate ([#9683](https://github.com/librenms/librenms/pull/9683)) - [murrant](https://github.com/murrant)
* Alert Rules: fix for critical and warning rule ([#9688](https://github.com/librenms/librenms/pull/9688)) - [kkrumm1](https://github.com/kkrumm1)
* Added Alertmanager transport ([#9637](https://github.com/librenms/librenms/pull/9637)) - [angryp](https://github.com/angryp)
* Fix wireless sensor edit messages and collection alert rule ([#9624](https://github.com/librenms/librenms/pull/9624)) - [murrant](https://github.com/murrant)
* Alert schedule refactor ([#9514](https://github.com/librenms/librenms/pull/9514)) - [murrant](https://github.com/murrant)

#### Feature
* Added Mattermost Alert Transport ([#9749](https://github.com/librenms/librenms/pull/9749)) - [gpant](https://github.com/gpant)
* Pressing enter on global search goes to the first result ([#9587](https://github.com/librenms/librenms/pull/9587)) - [murrant](https://github.com/murrant)
* Lnms bash completion ([#9747](https://github.com/librenms/librenms/pull/9747)) - [murrant](https://github.com/murrant)
* Hook many commands into the lnms script ([#9699](https://github.com/librenms/librenms/pull/9699)) - [murrant](https://github.com/murrant)
* Add lnms command ([#9619](https://github.com/librenms/librenms/pull/9619)) - [murrant](https://github.com/murrant)
* Allow grouping of sensors ([#9606](https://github.com/librenms/librenms/pull/9606)) - [murrant](https://github.com/murrant)
* Validate database constraints ([#9670](https://github.com/librenms/librenms/pull/9670)) - [murrant](https://github.com/murrant)

#### Bug
* Fix Exception in GraylogAPI.php ([#9617](https://github.com/librenms/librenms/pull/9617)) - [zoc](https://github.com/zoc)
* Fix devices page search & OS loading ([#9752](https://github.com/librenms/librenms/pull/9752)) - [murrant](https://github.com/murrant)
* Revert "Mattermost Alert Transport" ([#9743](https://github.com/librenms/librenms/pull/9743)) - [TheGreatDoc](https://github.com/TheGreatDoc)
* Validate default config seeder ([#9723](https://github.com/librenms/librenms/pull/9723)) - [murrant](https://github.com/murrant)
* Fix missing config setting in DB seed alert.transports.mail ([#9721](https://github.com/librenms/librenms/pull/9721)) - [murrant](https://github.com/murrant)
* Fix sql schema 278 ([#9715](https://github.com/librenms/librenms/pull/9715)) - [murrant](https://github.com/murrant)
* Alert Rules: fix for critical and warning rule ([#9688](https://github.com/librenms/librenms/pull/9688)) - [kkrumm1](https://github.com/kkrumm1)
* Fix if discover overwritting fields ([#9643](https://github.com/librenms/librenms/pull/9643)) - [evheros](https://github.com/evheros)
* Fix validate error ([#9700](https://github.com/librenms/librenms/pull/9700)) - [murrant](https://github.com/murrant)
* Update Mimosa.php ([#9695](https://github.com/librenms/librenms/pull/9695)) - [kiwibrew](https://github.com/kiwibrew)
* Rename librenms script to lnms ([#9696](https://github.com/librenms/librenms/pull/9696)) - [murrant](https://github.com/murrant)
* Seeds can run on existing ([#9689](https://github.com/librenms/librenms/pull/9689)) - [murrant](https://github.com/murrant)
* Run both legacy schema and migrations in the same run if needed ([#9686](https://github.com/librenms/librenms/pull/9686)) - [murrant](https://github.com/murrant)
* Fix dbSchema 1000 skipping schema files ([#9685](https://github.com/librenms/librenms/pull/9685)) - [murrant](https://github.com/murrant)
* Removed NO_AUTO_CREATE_USER from mysql strict to support MySQL 8 ([#9668](https://github.com/librenms/librenms/pull/9668)) - [laf](https://github.com/laf)
* Increase snmp execution time limit to 20 minutes ([#9639](https://github.com/librenms/librenms/pull/9639)) - [murrant](https://github.com/murrant)
* Add group to sensor 1st discovery + template syntax {{ $xxx }} ([#9667](https://github.com/librenms/librenms/pull/9667)) - [PipoCanaja](https://github.com/PipoCanaja)
* Order by support for availability map widget ([#9663](https://github.com/librenms/librenms/pull/9663)) - [murrant](https://github.com/murrant)
* Remove broken routeros signal sensor ([#9650](https://github.com/librenms/librenms/pull/9650)) - [murrant](https://github.com/murrant)
* Fix sentry3 voltage sensors ([#9649](https://github.com/librenms/librenms/pull/9649)) - [murrant](https://github.com/murrant)
* Fix wireless sensor edit messages and collection alert rule ([#9624](https://github.com/librenms/librenms/pull/9624)) - [murrant](https://github.com/murrant)
* Fix poller.php with missing -h ([#9621](https://github.com/librenms/librenms/pull/9621)) - [murrant](https://github.com/murrant)
* Fix Infoblox NIOS graphs ([#9620](https://github.com/librenms/librenms/pull/9620)) - [murrant](https://github.com/murrant)
* Fix .gitingore "changed" files with github-remove script ([#9616](https://github.com/librenms/librenms/pull/9616)) - [murrant](https://github.com/murrant)
* Fix orphaned dashboards ([#9590](https://github.com/librenms/librenms/pull/9590)) - [murrant](https://github.com/murrant)

#### Webui
* Pressing enter on global search goes to the first result ([#9587](https://github.com/librenms/librenms/pull/9587)) - [murrant](https://github.com/murrant)
* Fix devices page search & OS loading ([#9752](https://github.com/librenms/librenms/pull/9752)) - [murrant](https://github.com/murrant)
* Rewrite devices page backend (and a little frontend) ([#9726](https://github.com/librenms/librenms/pull/9726)) - [murrant](https://github.com/murrant)
* Handle db update errors better in the installer ([#9701](https://github.com/librenms/librenms/pull/9701)) - [murrant](https://github.com/murrant)
* Improve display for 802.1X NAC ([#9706](https://github.com/librenms/librenms/pull/9706)) - [PipoCanaja](https://github.com/PipoCanaja)
* Refactor FDB Tables to Laravel ([#9669](https://github.com/librenms/librenms/pull/9669)) - [murrant](https://github.com/murrant)
* Better IP exists feedback when adding a device ([#9697](https://github.com/librenms/librenms/pull/9697)) - [murrant](https://github.com/murrant)
* Order by support for availability map widget ([#9663](https://github.com/librenms/librenms/pull/9663)) - [murrant](https://github.com/murrant)
* Sort device select by hostname ([#9607](https://github.com/librenms/librenms/pull/9607)) - [murrant](https://github.com/murrant)
* Alert schedule refactor ([#9514](https://github.com/librenms/librenms/pull/9514)) - [murrant](https://github.com/murrant)
* Removed Legacy Transport UI https://t.libren.ms/deprecation-alerting ([#9552](https://github.com/librenms/librenms/pull/9552)) - [laf](https://github.com/laf)

#### Device
* Adding temp/humidity sensors for raritan px2 ([#9719](https://github.com/librenms/librenms/pull/9719)) - [sjtarik](https://github.com/sjtarik)
* FreeBSD mempools Fix ([#9659](https://github.com/librenms/librenms/pull/9659)) - [vitalisator](https://github.com/vitalisator)
* Adding Sonicwall SMA 400 support ([#9555](https://github.com/librenms/librenms/pull/9555)) - [marvink87](https://github.com/marvink87)
* Support for Alcatel OmniPCX ([#9375](https://github.com/librenms/librenms/pull/9375)) - [PipoCanaja](https://github.com/PipoCanaja)
* Improve index check for compatibility with different versions of the DDOS ([#9698](https://github.com/librenms/librenms/pull/9698)) - [acl](https://github.com/acl)
* Eltek Valere more sensors ([#9713](https://github.com/librenms/librenms/pull/9713)) - [murrant](https://github.com/murrant)
* New OS: Schleifenbauer, entity-physical improvements, various html page fixes ([#9471](https://github.com/librenms/librenms/pull/9471)) - [martijn-schmidt](https://github.com/martijn-schmidt)
* Huawei iBMC absent state grey ([#9691](https://github.com/librenms/librenms/pull/9691)) - [murrant](https://github.com/murrant)
* Nokia vrf bgp ([#9622](https://github.com/librenms/librenms/pull/9622)) - [vitalisator](https://github.com/vitalisator)
* Implement NAC data polling ([#9592](https://github.com/librenms/librenms/pull/9592)) - [PipoCanaja](https://github.com/PipoCanaja)
* Cable Modem Graphs for TopVision OS ([#9679](https://github.com/librenms/librenms/pull/9679)) - [djamp42](https://github.com/djamp42)
* Merge ethernetprobe2 into akcp and improve akcp ([#9465](https://github.com/librenms/librenms/pull/9465)) - [murrant](https://github.com/murrant)
* Sorting States using groups ([#9666](https://github.com/librenms/librenms/pull/9666)) - [PipoCanaja](https://github.com/PipoCanaja)
* Added ignore mount point effects macOS ([#9652](https://github.com/librenms/librenms/pull/9652)) - [kkrumm1](https://github.com/kkrumm1)
* EATON-MGEUPS: Added sensors for temperature and humidity from … ([#9647](https://github.com/librenms/librenms/pull/9647)) - [Kal42](https://github.com/Kal42)
* Remove broken routeros signal sensor ([#9650](https://github.com/librenms/librenms/pull/9650)) - [murrant](https://github.com/murrant)
* Fix sentry3 voltage sensors ([#9649](https://github.com/librenms/librenms/pull/9649)) - [murrant](https://github.com/murrant)
* Fix some issues with sensor limits ([#9638](https://github.com/librenms/librenms/pull/9638)) - [murrant](https://github.com/murrant)
* Added support for Vigintos Modulator & Ampiflier ([#9488](https://github.com/librenms/librenms/pull/9488)) - [jozefrebjak](https://github.com/jozefrebjak)
* Device Support for Pegasus ([#9641](https://github.com/librenms/librenms/pull/9641)) - [vitalisator](https://github.com/vitalisator)
* TopVision CMTS ([#9627](https://github.com/librenms/librenms/pull/9627)) - [djamp42](https://github.com/djamp42)
* Fix Infoblox NIOS graphs ([#9620](https://github.com/librenms/librenms/pull/9620)) - [murrant](https://github.com/murrant)
* ZyXEL Telemetry - XGS4600-32F ([#9599](https://github.com/librenms/librenms/pull/9599)) - [cppmonkey](https://github.com/cppmonkey)

#### Security
* Rewrite devices page backend (and a little frontend) ([#9726](https://github.com/librenms/librenms/pull/9726)) - [murrant](https://github.com/murrant)
* Rewrite netcmd and ripe whois tools ([#9724](https://github.com/librenms/librenms/pull/9724)) - [murrant](https://github.com/murrant)
* Update dependencies ([#9657](https://github.com/librenms/librenms/pull/9657)) - [murrant](https://github.com/murrant)
* Refactor FDB Tables to Laravel ([#9669](https://github.com/librenms/librenms/pull/9669)) - [murrant](https://github.com/murrant)

#### Documentation
* Update docs on mkdocs ([#9631](https://github.com/librenms/librenms/pull/9631)) - [emestee](https://github.com/emestee)
* New OS: Suggest -d in discovery.php to clear cache ([#9602](https://github.com/librenms/librenms/pull/9602)) - [murrant](https://github.com/murrant)
* FAQ LibreNMS and MIBs ([#9664](https://github.com/librenms/librenms/pull/9664)) - [murrant](https://github.com/murrant)
* Update Fast-Ping-Check.md ([#9705](https://github.com/librenms/librenms/pull/9705)) - [sanegaming](https://github.com/sanegaming)
* Update poller_modules documentation for NAC ([#9704](https://github.com/librenms/librenms/pull/9704)) - [PipoCanaja](https://github.com/PipoCanaja)
* Docs:Update SNMP-Trap-Handler.md ([#9654](https://github.com/librenms/librenms/pull/9654)) - [JoshWeepie](https://github.com/JoshWeepie)
* Oxidized JunOS syslog hook documentation fix ([#9676](https://github.com/librenms/librenms/pull/9676)) - [nova-2nd](https://github.com/nova-2nd)
* Reference config options for new beta poller service ([#9644](https://github.com/librenms/librenms/pull/9644)) - [Swashy](https://github.com/Swashy)


---


##[2013 Changelog](Changelogs/2013.md)

##[2014 Changelog](Changelogs/2014.md)

##[2015 Changelog](Changelogs/2015.md)

##[2016 Changelog](Changelogs/2016.md)

##[2017 Changelog](Changelogs/2017.md)

##[2018 Changelog](Changelogs/2018.md)