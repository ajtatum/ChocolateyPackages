ChocolateyPackages
==================

Repo of [Chocolatey](http://chocolatey.org/) packages that I use for different scenarios.

To Install Choclatey, run the following in Command Prompt with elevated privileges:

```
@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%systemdrive%\chocolatey\bin
```

After running, you may need to close out of that command prompt window and open it back up again. Then, simply type: cinst PackageName.config
