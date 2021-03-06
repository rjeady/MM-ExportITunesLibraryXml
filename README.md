# MediaMonkey Export to iTunes library.xml



Based on the original script posted by "DC" on the MediaMonkey forum to export to SqueezeCenter:

http://www.mediamonkey.com/forum/viewtopic.php?f=2&t=31680


My primary use-case for this script is to export the MediaMonkey library/playlists for use in Native Instruments TraktorDJ: as bridge to DJ software.


Tested:

| Software                      | Version   | OS          | Note                                                                    |
|-------------------------------|-----------|-------------|---------------------------------------------------------------|
| Media Monkey Gold             | 4.1.20.1864 | Windows 10 | OK                                                                     |
| Native Instruments Traktor DJ | 2.11.3 17 | Windows 10  | OK                                                                      |
| Native Instruments Traktor DJ | 2.11.3.17 | MacOS Sierra | tracks / playlists read OK, file location needs to be updated/remapped |
| Mixx                          | 2.0.0 x64 | Windows 10  | OK |
| Mixx                          | 2.1.1 x64 | Windows 10  | NOK - Tracks read OK; only 5 or so playlists shown | 
| Virtual DJ                    | 8.3 b4459 (2018) | Windows 10 | OK |
| Serato                        | TBD |              | Unknown, feedback wanted   |



Reports on compatibility/issues with other software welcome.


## Installation

Install the ExportITunesXML.mmip as MediaMonkey extension.

Build the binary from sources or download from the repository:
https://github.com/fvdpol/MM-ExportITunesLibraryXml/releases/latest



## History

### Version 1.0
- Script Original Version; by DC posted Wed Aug 06, 2008 3:01 pm
http://www.mediamonkey.com/forum/viewtopic.php?f=2&t=31680#p162175


### Version 1.2
- Update for Unicode ; by DC posted Sun Oct 10, 2010 6:21 pm
http://www.mediamonkey.com/forum/viewtopic.php?f=2&t=31680&start=60#p272344


### Version 1.3
- Fixed URI encoding, added Last Player; by VariableFlame posted Sun Jan 07, 2018 5:10 pm
http://www.mediamonkey.com/forum/viewtopic.php?f=2&t=31680&start=75#p441991

### Version 1.4
- Fixed: Traktor failing import due to invalid characters in xml (& -> &#38;); fvdpol, July 4 2018


### Version 1.5
- Update to add BPM field for Traktor; by Rhashime posted Sat Dec 24, 2011 12:14 pm
http://www.mediamonkey.com/forum/viewtopic.php?f=2&t=31680&start=60#p324753


- added forced export on shutdown; by Mazze_HH posted Wed Dec 12, 2012 3:51 am
- Update to export playlist structure to Traktor; by Mazze_HH posted Wed Dec 12, 2012 3:51 am
http://www.mediamonkey.com/forum/viewtopic.php?f=2&t=31680&start=60#p354155


### Version 1.6
- Migrated report to a standard script
- Added MediaMonkey package installer (ExportItunesXML.mmip)
- Added auto-update of script from GitHub repository


## Future changes/enhancements

- configuration settings for file location & flags (auto export, periodic export) 
- if needed: configurable quirks for compatibility with other appliciations
- document compatibility with other applications/dj software (feedback from users required)

