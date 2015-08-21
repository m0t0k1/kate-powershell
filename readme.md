# kate-powershell

# what is this?

This is the xml file that defines the syntax of the PowerShell for highlighting-kate.
To use this file you need to re- build to come to clone a highlighting-kate from Github repository .

```bash
mv powershell.xml /your/cloned/highlighting-kate/xml/.
cd /your/cloned/highlighting-kate
make prep
cabal install -fexecutable
```
