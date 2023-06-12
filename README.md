To download the RDP Wrapper from the GitHub repository, follow these steps:

Go to https://github.com/binarymaster/rdpwrap/releases in your web browser.

Look for the latest available version of the RDP Wrapper Library (v1.6.2) and click on it.

Download the appropriate ZIP file for your system architecture (x64 or x86).

Extract the contents of the ZIP file to a folder on your computer.

After following these steps, you should have successfully downloaded the RDP Wrapper from the GitHub repository. It's worth noting that although the project hasn't been updated since 2017, it can still be used in all new builds of Windows 10 and even Windows 11.

The current version of the rdpwrap.ini file can be downloaded here https://raw.githubusercontent.com/sebaxakerhtc/rdpwrap.ini/master/rdpwrap.ini

Manually copy the contents of this page to the “C:\Program Files\RDP Wrapper\rdpwrap.ini” file.

Or run this

```
Stop-Service termservice -Force
Invoke-WebRequest https://raw.githubusercontent.com/sebaxakerhtc/rdpwrap.ini/master/rdpwrap.ini -outfile "C:\Program Files\RDP Wrapper\rdpwrap.ini"
```
