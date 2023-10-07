# vscintellisenseinsublimetext

##EN

First type this code to cmd/terminal

``` 
  npm install -g typescript-language-server typescript
```

then install LSP package in Sublime Text

then type this code to LSP package settings

```
"clients": {
        "typescript-language-server": {
            "enabled": true,
            "command": [ "typescript-language-server", "--stdio" ], // Update the PATH
            "selector": "source.js"
        }
    }
```

and restart Sublime Text


## TR
Vscode'daki intellisensei sublime text'e getireceğiz.

ilk önce

``` 
  sudo npm install -g typescript-language-server typescript
```

sonra sublime text'de LSP paketini indiriyoruz.

Paket ayarlarına

```
"clients": {
        "typescript-language-server": {
            "enabled": true,
            "command": [ "typescript-language-server", "--stdio" ], // Update the PATH
            "selector": "source.js"
        }
    }
```

ekliyoruz ve yeniden başlatıyoruz.

Bu kadar.
