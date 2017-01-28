APK Unpack
==============================
## INTRO

This package and command-line helps you unpack any APK (get its smali sources) and decrypt its manifest.  
It contains 2 main methods:

### extract (apkfile, outputdir, onReadyCallback).  
This does the extraction of assets and sources into the given outputdir.  

### info (callback(err,data)).  
Retrieves decrypted manifest information about the extracted apkfile from method one.  

## USAGE
It comes with a commandline that you can use as follows:  

**apk_unpack** `apkfile.apk` `outputdir`

## UPDATES

version 1.0.7:
- Prettyfied readme.md file
- Fix for command-line call

version 1.0.3:
- Add readme.md file