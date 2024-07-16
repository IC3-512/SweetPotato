How to compile SweetPotato:

```
git clone https://github.com/CCob/SweetPotato
```
install vscode

install nuget.exe https://www.nuget.org/downloads
```
./nuget.exe restore
```
install .NET Framework 4.6.1 https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net461-developer-pack-offline-installer

Disable defender or set it to allow list!!!
```
dotnet publish -c Release -r win-x64 --self-contained
```

