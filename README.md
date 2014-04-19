wine-verb-arma2server
=====================

A winetricks verb for installing Arma 2 Operation Arrowhead through Steam under Wine into itss own prefix.

## Usage

```
$ git clone https://github.com/airtonix/wine-verb-arma2server.git
$ WINEARCH=win32 winetricks ./wine-verb-arma2server/arma2server_steam.verb
```

## Notes 

  - 32 bit is needed, because DotNet40 does not install under 64bit under Wine
  - If your ~/.wine is already 64bit, then wipe it. you should be using prefixes per application anyway.
  - This isn't totally automated yet. I might drop in button clicking.
