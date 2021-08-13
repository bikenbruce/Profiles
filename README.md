# Profiles
Profiles for Mobile Config

Find or list keys available:
```/usr/bin/security find-identity -p codesigning -v```
This will return the available signatures / code signing certificates that can be used.  Atul Pula is able to get code signing certs. 

And sign:
```/usr/bin/security cms -S -N "San Jose State University" -i /Volumes/nuts/DBH\ Labs\ dock.mobileconfig -o /Volumes/nuts/DBH-test.mobileconfig```
