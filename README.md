# MTR plugin for MobaXterm and Cygwin <a href="https://github.com/zhubanRuban/mtr-mobaxterm-plugin/"><img height="30" src="https://camo.githubusercontent.com/7710b43d0476b6f6d4b4b2865e35c108f69991f3/68747470733a2f2f7777772e69636f6e66696e6465722e636f6d2f646174612f69636f6e732f6f637469636f6e732f313032342f6d61726b2d6769746875622d3235362e706e67"></a> <a href="https://mobaxterm.mobatek.net/" target="_blank"><img align="right" height="40" src="https://mobaxterm.mobatek.net/img/moba/xterm_logo.png"></a> <a href="http://www.bitwizard.nl/mtr/" target="_blank"><img align="right" height="40" src="http://www.bitwizard.nl/img/bw_logo_new.png"></a>

Built from [MTR releases](https://github.com/traviscross/mtr/releases) with [fixes](https://github.com/traviscross/mtr/issues/199).

# [How to install](https://mobaxterm.mobatek.net/plugins.html)

> In order to install plugin, just download [.mxt3](https://github.com/zhubanRuban/mtr-mobaxterm-plugin/raw/master/mtr-0.92.mxt3) file and put it in the same directory than MobaXterm executable.

N.B. You can use all versions except for \*\_x64 as Mobaxterm is based on x86 (32-bit) version of Cygwin

## Cygwin users can also install the plugin:

### Cygwin x86

```
wget -qO mtr https://github.com/zhubanRuban/mtr-mobaxterm-plugin/raw/master/mtr-0.92.mxt3 && unzip mtr -d / && rm -f mtr
```

### Cygwin x64

```
wget -qO mtr https://github.com/zhubanRuban/mtr-mobaxterm-plugin/raw/master/mtr-0.93-x64.mxt3 && unzip mtr -d / && rm -f mtr
```

### [How to detect Cygwin installation bitness](https://stackoverflow.com/questions/22687184/how-do-i-tell-whether-my-cygwin-installation-is-32-or-64-bit)

>```
>uname -m
>```

### Uninstallation

```
wget -qO mtr https://github.com/zhubanRuban/mtr-mobaxterm-plugin/raw/master/mtr-0.92.mxt3 && unzip -Z1 mtr | xargs -I{} rm -vf /{} && rm -f mtr
```
